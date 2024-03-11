# Trello Clone - Aplicação Fullstack MEAN

Este projeto é um clone do Trello, construído com a pilha MEAN (MongoDB, Express, Angular e Node.js). Ele permite que você crie e gerencie quadros, listas e cartões, com suporte a comunicação em tempo real usando **WebSocket** com **Socket.IO**.

## Tecnologias Utilizadas

1. **Angular**: A estrutura de front-end que permite criar interfaces de usuário dinâmicas e responsivas.
2. **Typescript**: A linguagem usada para escrever código no lado do cliente e do servidor.
3. **Node.js**: O ambiente de tempo de execução JavaScript no servidor.
4. **Express**: O framework para construir aplicativos da web no Node.js.
5. **MongoDB**: O banco de dados NoSQL usado para armazenar dados do aplicativo.
6. **Socket.IO**: A biblioteca para comunicação em tempo real entre o cliente e o servidor.

## Funcionalidades Principais

- **Quadros**: Crie e gerencie seus quadros personalizados.
- **Listas**: Adicione listas às suas placas para organizar tarefas.
- **Cartões**: Crie cartões dentro das listas para representar tarefas específicas.
- **Comunicação em Tempo Real**: Use WebSocket com Socket.IO para atualizações em tempo real.

## Como Executar o Projeto

1. **Clone o Repositório**: `git clone https://github.com/seu-usuario/trello-clone.git`
2. **Instale as Dependências**:
   - No diretório raiz: `npm install`
   - No diretório `client`: `cd client && npm install`
3. **Configure o Banco de Dados**:
   - Certifique-se de ter o MongoDB instalado e em execução.
   - Edite o arquivo `.env` com as configurações do banco de dados.
4. **Inicie o Servidor e o Cliente**:
   - No diretório raiz: `npm start`
   - No diretório `client`: `cd client && ng serve`
5. **Acesse o Aplicativo**:
   - Abra o navegador e vá para `http://localhost:4200`.

## Contribua!

Se você quiser contribuir para este projeto, fique à vontade para abrir uma **pull request**. Vamos tornar este clone do Trello ainda mais incrível! 🚀

---

Espero que você se divirta explorando e desenvolvendo o seu Trello Clone! Se tiver alguma dúvida, não hesite em perguntar. 😊
