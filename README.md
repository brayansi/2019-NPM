
# Commands
* npm login
* npm publish
* npm version
    * major "Atualização grandes"
        * Ex: ">=1.0.1"
    * minor "Funcionaliddade novas"
        * Ex: "^1.0.1"
    * patch "Atualização minimas"
        * Ex: "^1.0.1"
        * Ex: "~1.0.1"

# Commands CLI

## User Commands

### login

##### Comando usado para fazer login. É necessário estar logado para poder publicar pacotes no registro do npm. Os dados são salvos no arquivo “.npmrc”

### logout

##### Faz logout da conta do npm, removendo os dados do “.npmrc”.

### whoami

##### Exibe o nome do usuário logado

## Package Management Commands

### install

##### Instala todos os pacotes especificados no “package.json”. Se o nome de um ou mais pacotes forem passados, eles serão instalados.

### uninstall

##### Usado para desinstalar um ou mais pacotes.

### ls

##### Lista os pacotes instalados

### outdated

##### Lista os pacotes desatualizados

### search

##### Faz uma busca de pacotes

### update

##### Atualiza os pacotes

### prune

##### Remove os pacotes instalados que não estão listados no “package.json”. Se houver uma variável de ambiente identificando que se está em um ambiente de produção, as dependências de desenvolvimento (devDependencies) serão apagadas.

## Publication Commands

### publish

##### Publica o pacote no registro do npm. É necessário estar logado para executar este comando.

### unpublish

##### Remove um pacote do registro do npm. Deve-se passar qual a versão será removida.

### deprecate

##### Marca o pacote como “obsoleto”. Isso irá exibir uma mensagem de alerta para quem instalar o pacote.

### version

##### Atualiza o número da versão do pacote. Deve-se especificar o tipo do versionamento: major, minor ou patch

## Others Commands

### cache

##### Usado para adicionar, listar ou limpar o cache do npm. Caso ocorram erros no npm, é muito útil tentar apagar o cache executando “$npm cache clean”

### config

##### Ajuda a gerenciar as configurações e variáveis de ambiente.

### init

##### Cria um arquivo “package.json”

### repo

##### Abre no navegador o endereço fornecido no campo “repository” do “package.json”.

### run

##### Executa um script fornecido no campo “scripts” do ”package.json”.

### help

##### Lista os comandos do npm. Se passar o nome de um comando, como “$ npm help install”, a documentação do comando será aberta.