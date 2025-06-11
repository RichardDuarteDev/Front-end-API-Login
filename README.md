Meu aplicativo de login
Este projeto é uma aplicação web simples que permite aos usuários efetuar login usando seu nome de usuário e senha. Consiste em uma página de login e uma página de área de trabalho onde rotas de API adicionais podem ser adicionadas.

Estrutura do Projeto
my-login-app
├── src
│   ├── index.html          # The login page
│   ├── workspace.html      # The workspace page for additional API routes
│   ├── css
│   │   └── styles.css      # CSS styles for the application
│   └── js
│       ├── login.js        # JavaScript for handling login functionality
│       └── workspace.js     # JavaScript for the workspace page
├── package.json            # Configuration file for npm
└── README.md               # Documentation for the project
Começando
Para executar este aplicativo, siga estas etapas:

Clonar o repositório :

git clone <repository-url>
cd my-login-app
Instalar dependências (se houver):

npm install
Abra o aplicativo : Abra src/index.htmlno seu navegador para acessar a página de login.

Uso
Página de login : digite seu nome de usuário e senha e clique no botão Enviar para efetuar login. O aplicativo enviará uma solicitação POST https://localhost:7267/Usuario/logincom as credenciais fornecidas.

Página do espaço de trabalho : após efetuar login, você pode navegar para src/workspace.htmlacessar funcionalidades adicionais e rotas de API.

Contribuindo
Se você quiser contribuir com este projeto, bifurque o repositório e envie um pull request com suas alterações.

Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter detalhes.
