# Olá! Eu sou o Rayldo Azevedo 👋

**Desenvolvedor Full‑Stack (Angular/NestJS/Node.js)** com foco em produtos web, automações e performance. Hoje construo soluções para e‑commerce e agendamentos esportivos, usando **Angular 19**, **NestJS/Node.js**, **TypeScript**, **MongoDB/PostgreSQL** e práticas modernas de **DevOps** (Docker, CI/CD, VPS e nuvem).

> *Busco oportunidades para contribuir com times que valorizem código limpo, testes, documentação e entrega contínua.*

---

## 🚀 Tech Stack (principal)

* **Front-end:** Angular 19, TypeScript, HTML5, CSS3, RxJS
* **Back-end:** NestJS, Node.js (Express/Fastify), REST, JWT/Auth
* **Banco de dados:** PostgreSQL, MongoDB, Prisma/Mongoose, Supabase
* **Infra & DevOps:** Docker, Git/GitHub, GitHub Actions, Vercel, Railway, VPS (Hostinger), n8n
* **Outros:** OCR (Tesseract / Cloud Vision), Webhooks, Axios/HTTP, ESLint/Prettier

> **Em estudo:** React (para projetos específicos), testes (Jest/Testing Library), arquiteturas orientadas a eventos.

---

## 📌 Projetos em destaque


* **Arena Mix – Agendamento de Campos**
  *Monorepo (Angular + NestJS) com autenticação, reservas e administração.*
  **Stack:** Angular 19, NestJS, PostgreSQL, Prisma, Docker, CI/CD.

* **Azevedo Móveis – Storefront**
  *Catálogo premium, carrinho simples e integração com WhatsApp.*
  **Stack:** Angular, Node/NestJS, MongoDB/PostgreSQL, Vercel.

* **Automations n8n**
  *Fluxos de automação (captura de leads, disparos, integrações).*
  **Stack:** n8n, Webhooks, APIs externas.

* **PetLove (Full Stack)**
  *Projeto acadêmico completo (frontend + backend).*
  **Stack:** JavaScript, Node, Mongo/Postgres.

* **Validador de Formulários (Regex)**
  *Utilitário de validação com exemplos práticos.*
  **Stack:** HTML, JS.

---

📫 Contato

Instagram: @rayrayazevedo https://www.instagram.com/rayrayazevedo/

WhatsApp: Fale comigo - https://wa.me/5562991472313

LinkedIn: https://www.linkedin.com/in/rayldo-azevedo-58346b184/
E-mail: rayldoazevedo@gmail.com

Dica: mantenha um e-mail profissional e um banner social (1200×630) no GitHub para reforçar sua marca.
## 🧩 Estrutura de repositórios (padrão sugerido)

```
root
├─ apps/ (front, api)
├─ packages/ (libs compartilhadas)
├─ docs/ (arquitetura, decisões ADR)
├─ .github/workflows/ (CI/CD)
└─ docker/ (Dockerfiles, compose)
```

## 🛠️ Templates úteis

### `.editorconfig`

```
root = true
[*]
charset = utf-8
end_of_line = lf
indent_style = space
indent_size = 2
insert_final_newline = true
trim_trailing_whitespace = true
```

### `.gitignore` (Node + Angular)

```
node_modules/
dist/
coverage/
.env*
.eslintcache
.angular/cache
**/*.log
```

### `docker-compose.yml` (exemplo simples API + DB)

```yml
services:
  api:
    build: ./api
    ports:
      - "3000:3000"
    env_file:
      - ./api/.env
    depends_on:
      - db
  db:
    image: postgres:16
    ports:
      - "5432:5432"
    environment:
      POSTGRES_USER: rayldo
      POSTGRES_PASSWORD: secret
      POSTGRES_DB: app
    volumes:
      - pgdata:/var/lib/postgresql/data
volumes:
  pgdata:


