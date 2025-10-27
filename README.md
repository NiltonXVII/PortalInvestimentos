Projeto Portal de Investimentos (PR) (Full-Stack)

Status: Em Desenvolvimento

Objetivo Principal

O objetivo é criar um portal de investimentos que analisa o perfil do investidor através de um quiz interativo (idade, experiência, objetivo, tolerância a risco). Com base nas respostas, o portal classifica o perfil (Conservador, Moderado, Arrojado) e recomenda produtos de investimento adequados. A interface do frontend foi estilizada para simular a identidade visual do Banco do Brasil. O backend (em desenvolvimento) fornecerá a API para salvar perfis e, potencialmente, buscar recomendações dinâmicas.

Tecnologias Utilizadas

Frontend (lado do cliente)

HTML5: Estruturação semântica da página do quiz e resultados.
CSS3: Estilização personalizada, incluindo o uso de variáveis CSS para o tema.
Bootstrap 5: Framework principal CSS para layout, componentes (modais, formulários, progress bar) e responsividade.
Bootstrap Icons: Biblioteca de ícones.
JavaScript (ES6+): Manipulação de eventos e lógica do quiz e cálculo de perfil.
jQuery: Utilizado para simplificar a manipulação do DOM e a interação com o formulário.

Backend (lado do servidor)

Node.js: Ambiente de execução para JavaScript no servidor.
Express.js: Framework para criação do servidor web e das rotas da API.
node-postgres (pg): Driver para a comunicação entre a aplicação Node.js e o banco de dados PostgreSQL.
CORS: Middleware para permitir que o frontend possa fazer requisições para a API.
PostgreSQL: Sistema de gerenciamento de banco de dados relacional.
