# Documentação Técnica do Aplicativo de Organização Acadêmica

## 1. Visão Geral do Projeto

### 1.1. Descrição do Projeto
O aplicativo de organização acadêmica tem como objetivo auxiliar estudantes no gerenciamento de suas disciplinas, horários de aulas e tarefas. Ele oferece funcionalidades como recomendações de disciplinas, um calendário interativo, notificações push e suporte offline por meio de Progressive Web App (PWA).

### 1.2. Tecnologias Utilizadas
- **Frontend:** React, React Router, Vite
- **Backend:** (Não determinado)
- **Banco de Dados:** (Não determinado)
- **Notificações Push:** Firebase Cloud Messaging (FCM)
- **Autenticação:** JSON Web Token (JWT)
- **PWA:** Vite Plugin PWA

## 2. Estrutura do Projeto

### 2.1. Estrutura do Frontend

```plaintext
academic-app/
├── public/
├── src/
│   ├── assets/          # Imagens, ícones
│   ├── components/      # Componentes reutilizáveis
│   ├── pages/           # Páginas principais
│   ├── routes/          # Configurações de rotas
│   ├── services/        # Consumo de APIs
│   ├── contexts/        # Gerenciamento de estado
│   ├── hooks/           # Hooks personalizados
│   ├── styles/          # Estilos globais
│   └── App.jsx
└── package.json
```

### 2.2. Estrutura do Backend

```plaintext
AcademicApp.API/
├── Controllers/         # APIs REST
├── Models/              # Modelos de dados
├── Data/                # Configuração do banco de dados
├── Services/            # Lógica de negócio
├── Repositories/        # Acesso a dados
├── DTOs/                # Transferência de dados
└── .....
```

## 3. Configuração do Ambiente

### 3.1. Requisitos
- **Node.js** (versão 16 ou superior)
- **Backend:** (Não determinado)
- **Banco de Dados:** (Não determinado)
- **Firebase Project** para notificações push

### 3.2. Configuração do Frontend

1. Instalar dependências:

   ```sh
   npm install
   ```

2. Iniciar o servidor de desenvolvimento:

   ```sh
   npm run dev
   ```

### 3.3. Configuração do Backend

(Não determinado)

## 4. Funcionalidades Implementadas
- Gerenciamento de Disciplinas
- Agenda e Calendário Interativo
- Autenticação de Usuários
- Notificações Push
- Suporte Offline e PWA

## 5. APIs Disponíveis
- **POST** `/api/auth/login`: Autentica o usuário e retorna um token JWT.
- **GET** `/api/disciplinas`: Retorna a lista de disciplinas.
- **POST** `/api/notifications/send`: Envia notificações push.

## 6. Boas Práticas Adotadas
- Organização de código com divisão por responsabilidades.
- Segurança: uso de JWT para autenticação e proteção de rotas.
- Tratamento de erros: middleware de exceções no backend.

## 7. Melhorias Futuras
- Integração com calendários externos (Google Calendar).
- Personalização de temas.
- Sistema de lembretes por e-mail.
- Integração com outros sistemas.

## 8. Contribuições
- **Desenvolvedores:** Marcello Santos, Luyze Caetano
- **Universidade:** Universidade do Estado do Pará

