# clone-tabnews
Um projeto para entender, criar e solidificar conhecimentos de fora a fora como funciona um projeto do zero.

## Versão do Node
Nesse projeto vamos utilizar o controle de versão do Node.js, ou <b>NVM</b>.

Iremos utilizar a versão <b><i>lts/hydrogen</b></i>

Para isso usamos o comando:

<code>nvm ls</code> -> Onde vamos listar todas as versões disponíveis.

<code>nvm install lts/hydrogen</code> -> Aqui selecionamos a versão  para instalação

<code>node -v</code> ->Verficamos se a instalação foi bem sucedida

No momento da criação desse projeto a versão utilizado foi <b>v18.20.8</b>

#
Outra prática é usar o comando:

<code>nvm --help</code> -> e olhar a documentação

Para garantir que o o sistema na hora de sua reinicialização não mude a versão do node, podemos fazer de duas formas:

<code>nvm alias default versao_desejada</code> ->Aqui setamos que o node com a versão desejada seja padrão no ambiente de desenvolvimento.

Outra forma é criar um arquivo <code>.nvmrc</code> onde o termo <b>RC</b> no final indica que temos um comando de inicialização ou <i>run commands</i>, onde vamos incializar o ambiente de desenvolvimento configurando o nvm com a versão lts/hydrogen.

Para que tudo funcione e quem abra seu projeto ou participe dele  use a versão recomendada por você, escreva dentro do arquivo `.nvmrc` na 1º linha a versão que deseja, no nosso caso `lts/hydrogen`, e em seguida criamos uma segunda linha em branco para que funcione.

Salvamos o arquivo e adicionamos a seguinte instrução a quem for abrir o projeto:

<h3>Abra seu terminal e inicialize digitando o seguindo comando:</h3>

`nvm install`

Com isso, o arquivo que configuramos irar setar automaticamente o node para versão correta.