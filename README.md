# 🚀 Node.js API REST com Fastify, Postgres e Deploy no Render

Este projeto foi desenvolvido como parte do curso [Node.js do Zero](https://www.youtube.com/watch?v=hHM-hr9q4mo) da Rocketseat. O objetivo é construir uma API REST utilizando Node.js, Fastify e Postgres, com deploy feito na plataforma [Render](https://render.com/) e banco de dados hospedado no [Neon](https://neon.tech/).

---

## 🗺️ Mapa da Jornada

Durante o curso, segui as etapas abaixo. Criei esse mapa visual para organizar o aprendizado:

![image](https://github.com/user-attachments/assets/10fbc213-6700-4d87-bc8e-5e12b71f4fca)

---

## 🧪 Tecnologias Utilizadas

- **Node.js**
- **Fastify**
- **PostgreSQL**
- **Neon.tech** (Database hosting)
- **Render.com** (Deploy da aplicação)

---

## 📂 Funcionalidades

- Criação de um servidor HTTP nativo com Node.js
- Configuração do Fastify para criação da API REST
- Manipulação de rotas com:
  - Request Body
  - Route Parameters
  - Query Parameters
- Banco de dados com:
  - DB em memória (inicialmente)
  - Integração com Postgres no Neon
  - Operações CRUD completas
- Deploy da API no Render

---

## 🧰 Instalação

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

# 2. Instale as dependências
npm install

# 3. Configure suas variáveis de ambiente (se necessário)
Crie um arquivo .env com suas credenciais do banco de dados

# 4. Rode o servidor
npm run dev
```

## 🌐 Link do Projeto Online

Você pode acessar a API hospedada no Render aqui:

👉 [https://nodejs-rocketseat-38i5.onrender.com/](https://nodejs-rocketseat-38i5.onrender.com/)
---

## 📨 Rotas da API

A API expõe as seguintes rotas:

### 📥 Criar um novo vídeo
- **POST** `/videos`
- Body (JSON):
  ```json
  {
    "title": "Título do vídeo",
    "description": "Descrição do vídeo",
    "duration": 120
  }
  ```

### 📤 Listar todos os vídeos
- **GET** `/videos`

### ✏️ Atualizar um vídeo
- **PUT** `/videos/:id`
- Body (JSON):
  ```json
  {
    "title": "Novo título",
    "description": "Nova descrição",
    "duration": 150
  }
  ```

### 🗑️ Deletar um vídeo
- **DELETE** `/videos/:id`
  
---

## 🧭 Roadmap de Estudos Recomendado

Após a criação da API REST com Fastify e Postgres, o próximo passo é continuar evoluindo seus conhecimentos com os tópicos abaixo:

- ✅ **APIs Nativas (FileSystem, Stream, Crypto)** 
- ✅ **TypeScript**
- ✅ **Autenticação JWT**
- ✅ **Princípios SOLID**
- ✅ **SQL (ORM – Prisma)**
- ✅ **Docker**
- ✅ **Frameworks (Fastify / NestJS)**
- ✅ **Testes automatizados (Jest / Vitest)**
- ✅ **Arquitetura de software**
- ✅ **Deploy & CI/CD**

---

## 📸 Créditos

A imagem do mapa foi criada por mim para representar visualmente a ordem dos tópicos abordados no curso da Rocketseat.

Aula completa: [https://www.youtube.com/watch?v=hHM-hr9q4mo](https://www.youtube.com/watch?v=hHM-hr9q4mo)
