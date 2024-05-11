Chat Bot
Um chat bot simples que utiliza a API do Google Generative AI (Gemini) para responder às mensagens dos usuários.

Funcionalidades
Envio de mensagens para o bot através do campo de entrada.
Respostas automáticas geradas pelo Google Generative AI.
Exibição das mensagens do usuário e do bot em uma interface de chat.
Como usar
Clone este repositório:

bash
Copy code
git clone https://github.com/seu-usuario/chat-bot.git
Abra o arquivo index.html em um navegador da web.

Digite sua mensagem no campo de entrada e pressione "Enviar".

Configuração da chave API
Para utilizar a API do Google Generative AI, é necessário fornecer uma chave API válida. Siga estas etapas para configurar a chave API:

Obtenha uma chave API do Google Cloud Console.

Crie um arquivo chamado API_key.js na raiz do projeto.

Dentro deste arquivo, defina sua chave API como uma variável:

javascript
Copy code
const API_KEY = "sua-chave-api-aqui";

export default API_KEY;
Certifique-se de não compartilhar essa chave publicamente.

Tecnologias Utilizadas
HTML
CSS
JavaScript (ES6)
Google Generative AI