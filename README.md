# ChatBotGPT

ChatBotGPT, desenvolvido em node.js, IA com a Api da Openai.

Tecnologias:

  OpenIA
  Venom-bot
  
 Para execução do ChatBotGPT, é necessário ter as seguintes instalações:
 
 Baixar o instalador no site oficial do Node.js (https://nodejs.org/en/download/) e seguir as instruções de instalação.
 
 Uma vez que você instalou o Node.js, você também terá o npm instalado automaticamente, o npm é o gerenciador de pacotes do Node.js
 ele permite instalar e gerenciar bibliotecas e dependências. Para verificar se você tem o Node.js e o npm instalados corretamente, 
 abra o prompt de comando e digite “node -v” e “npm -v” para ver as versões instaladas.
 
 Feito isso, abra o prompt comando e digite os seguintes comandos:
 
 
# Entre na pasta criada 
cd zap-gpt

Instalando o venom-bot
Como você já tem o arquivo package.json, já pode instalar as dependências do seu projeto. Você vai instalá-lo digitando “npm install venom-bot” no prompt de comando.

# Instale venom-bot como uma dependencia do seu projeto
npm install venom-bot

Agora da mesma forma que fizemos com o venom faremos com a dependência da openai, instale-a utilizando o comando “npm install openai” em seu terminal na 
raiz do projeto.

# Instale openai como uma dependencia do seu projeto
npm install openai
Para evitarmos futuros problemas como o vazamento da nossa api key e organization id vamos instalar também uma depencia chamada dotenv, 
que serve para criarmos variáveis de ambiente separadas do código.

# Instale dotenv como uma dependencia do seu projeto
npm install dotenv

# Pegar a API Key e Organization ID na OpenAI
A primeira coisa que precisamos aqui é da api key da openai, uma chave para autorização de envio das nossas requisições. 
Entre neste link para pegar sua chave https://beta.openai.com/account/api-keys, é bem auto explicativo.

Para pegar o organization ID também é bem fácil, é só acessar este link e copiar o seu ID https://beta.openai.com/account/org-settings

ChatBotGpt, base desenvolvida no site: https://medium.com/@victorhcharry/guia-completo-de-como-integrar-o-gpt-com-whatsapp-da9040341859

Com melhorias para múltiplas sessões para celulares diferentes, gerando Qrcode aleatoriamente.
