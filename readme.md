# Mapfit

## Descrição do Projeto

O Mapfit é um aplicativo que tem como objetivo apresentar locais no município de Recife, facilitando o acesso à informação sobre lugares adequados para a prática de atividades físicas. O aplicativo busca incentivar e promover a prática de exercícios físicos na cidade, fornecendo aos usuários uma lista de locais recomendados e informações relevantes para cada local.

## Funcionalidades

- Exibição de locais adequados para a prática de exercícios físicos em Recife
- Detalhes e informações sobre cada local, como descrição, horários de funcionamento.
- Recursos de pesquisa para encontrar locais específicos
- Integração com mapas para visualizar a localização dos lugares

## Tecnologias Utilizadas

- React Native com Expo: Framework para o desenvolvimento de aplicativos móveis multiplataforma
- MongoDB: Banco de dados utilizado para armazenar informações sobre os locais
- Node.js: Plataforma de desenvolvimento backend utilizada para criar a API do aplicativo

## Como usar

1. Certifique-se de ter o Node.js instalado em sua máquina.
2. Faça o clone do repositório do Mapfit: `git clone <URL_DO_REPOSITÓRIO>`
3. Navegue até o diretório do projeto: `cd mapfit`
4. Instale as dependências do projeto: `npm install`
5. Configuração do banco de dados MongoDB:
   - Crie um banco de dados no MongoDB
   - Configure as informações de conexão no arquivo de configuração `server/config/database.js`
6. Inicialize o servidor backend:
   - Navegue até o diretório do servidor: `cd server`
   - Inicie o servidor: `npm start`
7. Inicialize o aplicativo móvel:
   - Navegue até o diretório do aplicativo móvel: `cd mobile`
   - Inicie o aplicativo: `expo start`

