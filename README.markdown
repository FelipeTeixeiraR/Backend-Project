# 🚀 ROTEIRO COMPLETO BACKEND — Obsidian Edition

> [!NOTE]
> **Objetivo:** tornar-se um desenvolvedor backend completo e empregável.  
> **Duração sugerida:** 6–8 meses | **Carga semanal:** 10–15h  
> **Foco:** Node.js, TypeScript, PostgreSQL, Docker, Python (FastAPI), CI/CD e APIs modernas.  
>  
> Estruturado em pequenos passos para progresso real e consistente.  

---

# 🩵 ETAPA 1 — Fundamentos + Git (Semanas 1–3)

## 🎯 Por que
Entender lógica, terminal, versionamento e noções web é o alicerce de todo backend.

> [!TIP]
> Objetivo: dominar lógica, comandos básicos de terminal, Git e fundamentos de HTTP/JSON.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| ☑️ | Lógica de programação | Variáveis, tipos, operadores, condicionais e loops |
| ☑️ | Funções e escopo | Parâmetros, retorno e reutilização de código |
| 🟡 | Estruturas de dados | Arrays, objetos e manipulação com `map`, `filter`, `reduce` |
| 🔲 | Conceitos HTTP e JSON | Entender requisição, resposta e status codes |
| 🔲 | Terminal | Criar e executar scripts no terminal |
| 🔲 | Git básico | `init`, `add`, `commit`, `branch`, `push` e `merge` |
| 🔲 | Repositório no GitHub | Criar um repositório e publicar scripts simples |

> [!IMPORTANT]
> **Projeto Final:**  
> Crie 3 scripts básicos (ex: calculadora, lista de tarefas, parser JSON) e publique com README no GitHub.

---

# 🟦 ETAPA 2 — JavaScript + Node.js + Express (Semanas 4–8)

## 🎯 Por que
Node é a base do backend moderno. Aprender JavaScript e Express é essencial para construir APIs profissionais.

> [!NOTE]
> Conexão: aplica fundamentos de lógica e Git em servidores reais.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | JavaScript moderno | `let`, `const`, arrow functions, destructuring |
| 🔲 | Assíncrono | Entender Promises e `async/await` |
| 🔲 | Node.js básico | `npm init`, módulos (`fs`, `http`), import/export |
| 🔲 | Estrutura de projeto | Rotas, controladores, organização de pastas |
| 🔲 | Express básico | Criar rotas GET, POST, PUT, DELETE |
| 🔲 | Middlewares | Criar logs e tratamento de erros |
| 🔲 | Status e respostas | Enviar códigos HTTP corretos e JSON padrão |
| 🔲 | Testar API | Usar Postman ou Insomnia |

> [!IMPORTANT]
> **Projeto Final:**  
> Desenvolva sua **primeira API REST** com Express.js (CRUD completo).  
> Documente endpoints e publique no GitHub.

---

# 🟩 ETAPA 3 — TypeScript (Semanas 9–11)

## 🎯 Por que
TypeScript dá segurança e escalabilidade, sendo padrão em equipes profissionais.

> [!NOTE]
> Conexão: refatora a API anterior, adicionando tipagem e boas práticas.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | Configuração | Criar `tsconfig.json`, usar `ts-node` |
| 🔲 | Tipos e interfaces | Aplicar tipagem em funções e objetos |
| 🔲 | Classes e módulos | Estruturar código com orientação a objetos |
| 🔲 | Refatorar API | Converter para TypeScript (rotas e controladores) |
| 🔲 | Validação | Implementar `class-validator` ou `zod` |
| 🔲 | Estrutura de pastas | `src/`, `routes/`, `controllers/`, `services/` |

> [!IMPORTANT]
> **Projeto Final:**  
> API Express totalmente em TypeScript, validada e tipada.

---

# 🟧 ETAPA 4 — Banco de Dados (PostgreSQL) (Semanas 12–15)

## 🎯 Por que
Persistência de dados é essencial. PostgreSQL é o banco padrão em backends modernos.

> [!NOTE]
> Conexão: você integrará o banco real à sua API TypeScript.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | SQL básico | `SELECT`, `INSERT`, `UPDATE`, `DELETE`, `JOIN` |
| 🔲 | Modelagem | Tabelas, PK, FK, normalização simples |
| 🔲 | Instalação | PostgreSQL local ou via Docker |
| 🔲 | ORM | Configurar Prisma e migrations |
| 🔲 | CRUD persistente | Conectar API ao banco |
| 🔲 | Seeds e .env | Popular dados e proteger credenciais |

> [!IMPORTANT]
> **Projeto Final:**  
> API completa com PostgreSQL + Prisma ORM e CRUD funcional.  

---

# 🟨 ETAPA 5 — Docker e Ambientes (Semanas 16–18)

## 🎯 Por que
Containerização padroniza ambientes, evitando erros e facilitando deploys.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | Conceito | Entender containers e imagens |
| 🔲 | Dockerfile | Criar build da API |
| 🔲 | docker-compose | Subir API + banco simultaneamente |
| 🔲 | Variáveis | Usar `.env` e volumes persistentes |
| 🔲 | Testar stack | Rodar `docker-compose up` |
| 🔲 | Documentar | Descrever comandos no README |

> [!IMPORTANT]
> **Projeto Final:**  
> API e DB rodando 100% via Docker Compose, com documentação de uso.

---

# 🟪 ETAPA 6 — Python + FastAPI (Semanas 19–22)

## 🎯 Por que
Python expande suas possibilidades para IA, automação e microserviços.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | Sintaxe Python | Listas, dicts, funções, async básico |
| 🔲 | Ambiente | venv, pip, dependências |
| 🔲 | FastAPI | Criar rotas e respostas JSON |
| 🔲 | Swagger | Documentação automática |
| 🔲 | JWT | Implementar autenticação |
| 🔲 | Banco | SQLAlchemy + PostgreSQL |
| 🔲 | Docker | Containerizar microserviço |

> [!IMPORTANT]
> **Projeto Final:**  
> Microserviço FastAPI autenticado (JWT + PostgreSQL), documentado via Swagger.

---

# 🟥 ETAPA 7 — APIs Avançadas (Semanas 23–26)

## 🎯 Por que
APIs modernas exigem autenticação, documentação e flexibilidade.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | REST avançado | Padrões, versionamento, erros |
| 🔲 | JWT avançado | Refresh tokens, expiração |
| 🔲 | GraphQL | Schemas, resolvers, mutations |
| 🔲 | Swagger completo | Documentar todas rotas |
| 🔲 | Testes | Jest (Node) ou Pytest (Python) |

> [!IMPORTANT]
> **Projeto Final:**  
> API híbrida (REST + GraphQL), segura, testada e documentada.

---

# 🟫 ETAPA 8 — CI/CD + Deploy (Semanas 27–30)

## 🎯 Por que
CI/CD garante qualidade e entrega contínua, padrão de times profissionais.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | GitHub Actions | Configurar pipeline automatizado |
| 🔲 | Testes no pipeline | Rodar Jest/Pytest antes do deploy |
| 🔲 | Deploy automático | Render, Railway ou AWS |
| 🔲 | Variáveis ambiente | Configurar `.env` no servidor |
| 🔲 | Monitoramento | Healthchecks e logs básicos |

> [!IMPORTANT]
> **Projeto Final:**  
> Pipeline GitHub Actions com testes e deploy automático.

---

# ⬛ ETAPA 9 — Portfólio e Polimento (Semanas 31–34)

## 🎯 Por que
Transforma aprendizado em prova concreta de competência.

| ✅ | Meta Prática | Descrição |
|:--|:--------------|:-----------|
| 🔲 | Revisar código | Melhorar estrutura e limpeza |
| 🔲 | README profissional | Badges, instruções e exemplos |
| 🔲 | Publicar links | LinkedIn, GitHub e Deploys |
| 🔲 | Preparar apresentação | Pitch técnico de 2 minutos |

> [!IMPORTANT]
> **Projeto Final:**  
> Portfólio com 2 projetos deployados, documentação completa e perfil otimizado.

---

# 🧠 DICA FINAL
> [!TIP]
> - Reforce fundamentos sempre que sentir dificuldade.  
> - Documente tudo no GitHub.  
> - Faça commits pequenos e descritivos.  
> - Releia suas APIs após cada etapa.  
> - **Pequenos passos constroem grandes devs.**
