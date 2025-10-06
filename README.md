# Olá! Eu sou o Rayldo Azevedo 👋
<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExOG94bDI2M2ltNWpoMXU3YXo0OHVscXFqY2UyODJ4OG5pbXc2ZDFxYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xT1XGC8nIdwGgjgpa0/giphy.gif" width="200px"  />

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

> Sugestões de repositórios para fixar (Pins) no seu perfil:

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

> Dica: Se algum desses ainda não estiver público, crie os repositórios com README e roadmap. Use labels/issues para backlog e milestones para o planejamento.

---

## 🧩 Estrutura de repositórios (padrão sugerido)

```
root
├─ apps/ (front, api)
├─ packages/ (libs compartilhadas)
├─ docs/ (arquitetura, decisões ADR)
├─ .github/workflows/ (CI/CD)
└─ docker/ (Dockerfiles, compose)
```

* **Commits semânticos:** `feat:`, `fix:`, `chore:`, `docs:`, `refactor:` …
* **Branches:** `main` (estável), `dev` (integração), `feat/<nome>`, `fix/<nome>`
* **Padrões de PR:** checklist de testes, screenshots, notas de deploy.

---

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
```

### CI – GitHub Actions (build & lint Angular)

```yml
name: CI Front
on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: 20
          cache: 'npm'
      - run: npm ci
      - run: npm run lint
      - run: npm run build
```

---

## 📫 Contato

* **Instagram:** [@azevedomoveis](https://instagram.com/) *(ajuste para o seu real)*
* **WhatsApp:** [Fale comigo](https://wa.me/5599999999999) _(substituir pelo seu número)
* **LinkedIn:** (link)
* **E-mail:** (se quiser exibir)

> Dica: mantenha **um e-mail profissional** e um **banner social** (1200×630) no GitHub para reforçar sua marca.

---

## 📊 Métricas (opcional)

Você pode adicionar estatísticas com esses projetos open source:

```md
![Rayldo GitHub stats](https://github-readme-stats.vercel.app/api?username=RayldoAzevedo&show_icons=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=RayldoAzevedo&layout=compact)
```

> Evite métricas se ficarem desatualizadas; mantenha só o que agrega valor visual.

---

## ✅ Checklist para deixar o perfil redondo

* [ ] Atualizar bio: **Desenvolvedor Full‑Stack | Angular/NestJS/Node | Docker | PostgreSQL/Mongo**
* [ ] Fixar (Pin) 6 repositórios mais relevantes
* [ ] Adicionar tópicos (topics) nos repos: `angular`, `nestjs`, `nodejs`, `postgresql`, `mongodb`, `docker`, `supabase`, `automation`, `ecommerce`, `scheduling`
* [ ] Criar `README.md` com este conteúdo no repositório **`RayldoAzevedo/RayldoAzevedo`**
* [ ] Ajeitar links de contato (Instagram/WhatsApp/LinkedIn)
* [ ] Subir banner social com sua identidade visual
* [ ] Configurar Actions básicas (lint/build/test)

---

> **Nota importante:** Removi menções antigas (ex.: *Fox Grãos*) e foquei no que você vem usando hoje (Angular 19, NestJS/Node, Docker, PostgreSQL/Mongo, Supabase, Vercel/Railway, n8n, OCR). Ajuste os links e números onde indicado.






![Rayldo GitHub stats](https://github-readme-stats.vercel.app/api?username=RayldoAzevedo&show_icons=true&theme=radical)
