Allan Chat - Backend
Este repositório contém o backend do sistema de chat em tempo real. Ele é responsável pela lógica de negócios, autenticação, armazenamento de mensagens e comunicação com o frontend via WebSockets. O backend foi desenvolvido em Node.js com TypeScript e segue as melhores práticas para escalabilidade, segurança e performance.

Funcionalidades
Autenticação de usuários com OAuth2 e 2FA.
WebSockets para comunicação em tempo real com o frontend.
Gerenciamento completo de usuários (CRUD).
Sistema de cache usando Redis para melhorar a performance.
Elasticsearch para indexação e busca avançada de mensagens.
Prevenção de vulnerabilidades de segurança como SQL Injection, XSS e CSRF.
Estrutura pronta para escalabilidade e integração com filas para processamento assíncrono.
Tecnologias Utilizadas
Node.js com TypeScript: Para um desenvolvimento robusto e escalável.
PostgreSQL: Banco de dados relacional para armazenar informações de usuários e mensagens.
Redis: Utilizado como cache para melhorar a performance do sistema.
Elasticsearch: Utilizado para realizar buscas eficientes de mensagens e conversas.
OAuth2: Autenticação segura para proteger o sistema.
WebSockets: Para comunicação em tempo real com o frontend.
uWebSockets.js: Utilizado para comunicação eficiente via WebSocket.
Docker: Para containerização e facilidade de deploy.
Jest: Framework de testes para garantir qualidade de código com cobertura mínima de 80%.
Como Configurar o Backend
Requisitos
Node.js v18.x ou superior
PostgreSQL
Redis
Elasticsearch
Docker (opcional, se você usar contêineres)
