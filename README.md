# DexKeeper
Aplicação web de gerenciamento de Pokémon e Treinadores

## Descrição
DexKeeper é uma aplicação CRUD web desenvolvida para facilitar o gerenciamento de Pokémon e Treinadores. Criado como um projeto educativo, DexKeeper permite criar, editar e visualizar equipes de Pokémon, registrar e gerenciar treinadores, além de oferecer uma experiência prática no desenvolvimento web full-stack. Este projeto visa consolidar habilidades em arquitetura de software, integração front-end e back-end, autenticação de usuários e modelagem de dados, sendo também uma excelente adição ao currículo dos desenvolvedores.

## Principais Funcionalidades
- **CRUD de Pokémon**: Permite a inclusão, edição, exclusão e visualização de dados de Pokémon.
- **Gerenciamento de Treinadores**: Cadastro e gerenciamento de treinadores, incluindo a possibilidade de criar equipes de até 6 Pokémon.
- **Autenticação de Usuários**: Segurança de acesso para garantir que apenas usuários autenticados possam gerenciar os dados.
- **Perfil do Treinador**: Página dedicada a exibir as informações e equipe de cada treinador.

## Tecnologias Utilizadas
- **Back-End**: Node.js (Express) ou Django
- **Front-End**: React ou Vue.js
- **Banco de Dados**: PostgreSQL ou SQLite
- **Autenticação**: JWT (JSON Web Tokens)

## Estrutura do Projeto
DexKeeper/

- backend/ # Código e configuração do back-end

- models/ # Modelos de dados (Pokémon, Treinador)
- controllers/ # Lógica de controle para cada rota
- routes/ # Definição das rotas CRUD
- middleware/ # Middlewares (como autenticação)
- config/ # Configurações, como banco de dados e JWT
- app.js # Arquivo principal do servidor
- frontend/ # Código e configuração do front-end

- components/ # Componentes reutilizáveis (ex: Navbar, Footer)
- pages/ # Páginas principais (Home, Perfil do Treinador)
- services/ # Serviços de API para comunicação com o back-end
- assets/ # Arquivos estáticos (imagens, CSS)
- App.js # Componente principal do React/Vue
- README.md # Documentação do projeto

## Roadmap de Desenvolvimento

- [ ] Configuração do ambiente e dependências
  - Configuração do repositório Git e organização inicial
  - Configuração do ambiente Node.js e/ou Django
  - Configuração do banco de dados (PostgreSQL ou SQLite)
  
- [ ] Implementação do CRUD de Pokémon
  - Criação da estrutura de rotas e controladores para Pokémon
  - Configuração da tabela de Pokémon no banco de dados
  - CRUD completo (criação, edição, listagem, exclusão) para Pokémon
  
- [ ] Gerenciamento de Treinadores e Equipes
  - Criação da tabela de Treinadores e relacionamento com Pokémon
  - CRUD completo para Treinadores
  - Interface de gerenciamento de equipes de Pokémon

- [ ] Autenticação e autorização de usuários
  - Implementação de registro e login de usuários
  - Configuração do JWT para autenticação segura
  - Autorização de acesso para áreas restritas
  
- [ ] Estilização e design responsivo
  - Implementação de layout básico e estrutura do front-end
  - Estilização das páginas principais (Pokémon, Treinadores, Perfil)
  - Adaptação responsiva para dispositivos móveis
  
- [ ] Testes e ajustes finais
  - Testes de funcionalidade para o CRUD e autenticação
  - Revisão de código e documentação
  - Preparação para deploy em ambiente de produção
