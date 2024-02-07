### Projeto de automação com Postman e Report com Newman

Projeto de automação com Postman

## Instalação
```bash
    npm install -g newman
    npm install -g newman-reporter-htmlextra
```

## Execução com report html extra
```bash
    newman run signup.json -e env-automacao.json -g env-global.json
```

## Git e GitHub

No Git e GitHub, realize as seguintes etapas:

### **Instalar e Configurar uma conta no Git** 

Instale e Configure uma conta no Git. Para saber mais, [acesse o Git](https://git-scm.com/download/win).

### **Para clonar o repositório do Git**

 ```sh default
 git clone git@github.com:thais-telles/shortcircuit-academy-postman.git
 ```

### **Verificando se tem alterações no repositório Git e baixar para o repositório local**

 ```sh default
 git pull
 ```

### **Transferindo arquivos do repositório local para o repositório Git** 

Dentro do repositório local, abra o Git Bash e siga os seguintes passos:

 1. Adicionar todos os ficheiros alterados
 ```sh default
 git add .
 ```
 2. Colocar na zona de "preparação do computador"
 ```sh default
 git commit -m "nome ou descrição da inclusão ou alteração"
 ```
 3. Criar nome para as versões
 ```sh default
 git tag -a vx.x -m "version x.x"
 ```
 4. Para carregar as alterações no Git
 ```sh default
 git push origin main
 ```

 <p align="center">
  <img src="./.images/transferindo_alteracoes.png" alt="verifica chaves SSH existentes" width="60%" />

## Projeto Desenvolvido por: 
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/137322187?v=4" width=90><br/><sub>Danielle Sousa</sub>](https://github.com/thais-telles)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thais-telles/)]
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |