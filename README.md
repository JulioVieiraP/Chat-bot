# Chat Bot

Este é um projeto de um chat bot que utiliza a API do Google Generative AI para gerar respostas automáticas.

## Como usar

1. Clone este repositório para o seu ambiente local.
2. Crie um arquivo `API_key.js` na raiz do projeto e adicione sua chave de API do Google Generative AI nele da seguinte forma:

    ```javascript
    const API_KEY = "sua-chave-de-api-aqui";
    export default API_KEY;
    ```

    Certifique-se de não compartilhar sua chave de API publicamente, pois isso pode expor suas credenciais.

3. Abra o arquivo `index.html` em um navegador da web.
4. Digite uma mensagem na caixa de entrada e pressione "Enviar" para interagir com o chat bot.

## Estrutura do Projeto

- **index.html:** Contém a estrutura HTML da aplicação.
- **style.css:** Arquivo CSS para estilização da interface do chat bot.
- **API_key.js:** Arquivo que contém a chave de API do Google Generative AI (não incluído no repositório).
- **script.js:** Arquivo JavaScript que controla a lógica do chat bot.

## Dependências

- [@google/generative-ai](https://esm.run/@google/generative-ai): API do Google Generative AI para geração de respostas automáticas.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests com melhorias ou correções.
