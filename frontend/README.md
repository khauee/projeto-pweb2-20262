# Frontend — Marketplace IFPB Cajazeiras

Aplicação web do Marketplace Universitário do IFPB Campus Cajazeiras, construída com React, TypeScript, Vite, React Router, Redux Toolkit (thunks), componentes de UI próprios e Storybook.

Requisitos da Etapa 1: [`../docs/etapa-1.md`](../docs/etapa-1.md).

## Como rodar

```bash
# 1) Backend e banco de dados (na raiz do repositório)
cp .env.example .env
docker compose up --build        # API em http://localhost:8080 (Swagger em /swagger-ui.html)

# 2) Frontend
cd frontend
npm install
npm run dev                      # Aplicação em http://localhost:5173
npm run storybook                # Storybook em http://localhost:6006