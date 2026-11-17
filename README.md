<h1 align="center">Antonio Paulo Fidel</h1>

<p align="center">
  <b>Desenvolvedor Full-Stack · DevOps · IA aplicada</b><br/>
  Estudante de Engenharia de Software na ULBRA Palmas (TO)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/antoniopaulopereirafidel/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:antoniopfdl.fidel@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
</p>

---

Construo sistemas de ponta a ponta: **API, front web e mobile, banco de dados, contêineres, CI e deploy**. Nos projetos mais recentes tenho trabalhado com **IA aplicada**: busca semântica com embeddings, RAG com citação de fontes, OCR e roteamento de intenções com LLMs.

Gosto de trabalhar em equipe com fluxo de verdade: branches por funcionalidade, PRs pequenos, commits convencionais, testes automatizados e CI barrando o que quebra.

## 💼 Experiência

**MR Info** · Desenvolvedor Freelancer (remoto) · *set/2026 – atual*
- Integração com API de **emissão automática de NF-e** seguindo a Reforma Tributária
- Correção de vulnerabilidade de **acesso a arquivos sem autenticação**
- **Dashboard de monitoramento** de infraestrutura em tempo real e **fila de requisições** para o acesso a vídeos da plataforma
- Manutenção e melhorias em sistemas WordPress

**SENAI-TO** · Estagiário de TI e Inovação · *ago/2026 – atual*
- Suporte a unidades do SENAI em todo o Tocantins, extração de dados para relatórios gerenciais e troubleshooting de sistemas internos

**Mix Alimentos** · *fev/2025 – jun/2026*: comecei como estagiário e saí como desenvolvedor full-stack
- **Dev Full-Stack** *(abr – jun/2026)*: módulos do portal corporativo em **Django + React/TypeScript** (logística, prospecção comercial e autoatendimento de senha), **CI/CD com GitHub Actions**, refatoração de legado em **Laravel** e modelagem de bancos **SQL Server e Oracle**
- **Analista de Suporte de TI** *(fev – abr/2026)*: **Nginx/Apache** para serviços internos e externos, ambientes de homologação e produção equivalentes, **Firewall e NAT**, suporte a bancos Oracle
- **Estagiário de TI** *(fev/2025 – jan/2026)*: monitoramento com **Zabbix + Grafana**, interfaces em React e automações em Python

**22º Batalhão** · Auxiliar de TI · *jan/2023 – mai/2024*
- Suporte e manutenção de equipamentos, controle de ativos e configuração de **túneis IPsec**

---

## 🚀 Projetos em destaque

### 🔥 IGNIS: plataforma de estudos com Pomodoro, gamificação e IA
App (web e mobile) para ciclos de estudo com Pomodoro, metas, conquistas e um **assistente de IA que responde com base no material do aluno**. O aluno envia PDFs e imagens; o sistema extrai o texto (OCR), divide em trechos, faz **busca semântica com embeddings locais** e responde **citando a fonte (arquivo e página)**. Também gera resumos, flashcards e quizzes.

`NestJS` `Prisma` `PostgreSQL` `MongoDB` `React Native / Expo` `TypeScript` `LLM (Groq)` `Tesseract OCR` `Docker` `Caddy` `GitHub Actions` `Jest`

➡️ [Frontend](https://github.com/AntonioPauloFidel/Ignis_FrontEnd) · [Backend](https://github.com/saviodev0/IGNIS_Back_end), com cerca de 140 commits meus entre os dois repositórios

### 🧭 Culture OS: gestão de cultura e desempenho de pessoas
Plataforma de RH que junta **presença, OKRs, avaliação 360° e potencial** numa tela só e posiciona cada colaborador no **9-Box**. Tem permissões por grupo aplicadas na API e na tela, organograma, trilha de auditoria e um assistente que **responde perguntas sobre a documentação** com um modelo local.

`FastAPI` `PostgreSQL + pgvector` `Redis` `Ollama` `React` `TypeScript` `Vite` `Docker Compose` `GitHub Actions`

➡️ Repositório privado da equipe BitStudioLabs. Fui o principal contribuidor, com mais de 250 commits.

### 🦷 SIRDE: rastreabilidade de dentes para biobanco odontológico
Sistema para receber, catalogar, armazenar e ceder dentes humanos doados a cursos de Odontologia, com rastreabilidade e controle de acesso.

`TypeScript` `Express` `Prisma` `PostgreSQL` `JWT` `Vitest` `React` `Vite`

➡️ [Backend](https://github.com/AntonioPauloFidel/sistema_rastreabilidade_dentario_back_end) · [Frontend](https://github.com/AntonioPauloFidel/sistema_rastreabilidade_dentario_frontend)

### 🛡️ TankIO / TankScript: linguagem própria + jogo tático
Uma **linguagem de domínio específico** criada do zero, com gramática em ANTLR, análise semântica e interpretador. Ela controla um jogo de tanques e submarinos com névoa de guerra, IA adversária e interface web em Phaser.

`Python` `ANTLR` `Compiladores` `Phaser` `Docker` `pytest`

➡️ [Repositório](https://github.com/AntonioPauloFidel/Domain-Specific-Language)

---

## ☁️ Computação em Nuvem e DevOps

| Projeto | O que mostra |
|---|---|
| [docker-django](https://github.com/AntonioPauloFidel/docker-django) | Django + Gunicorn atrás de **Nginx** (proxy reverso e estáticos) com **PostgreSQL**, multi-container com Compose |
| [cn-mensagens-distribuidas](https://github.com/AntonioPauloFidel/cn-mensagens-distribuidas) | Sistema de mensagens com **3 instâncias Flask**, volume compartilhado e rede bridge personalizada, com script de testes em shell |
| [servicos-com-docker](https://github.com/AntonioPauloFidel/servicos-com-docker) | API FastAPI conteinerizada com persistência em volume e relatório de otimização da imagem |
| [python-mongodb-redis](https://github.com/AntonioPauloFidel/python-mongodb-redis) | CRUD em MongoDB com **cache em Redis**, os dois em Docker |

## 🧪 Outros projetos

| Projeto | Stack |
|---|---|
| [Controle de gastos residenciais](https://github.com/AntonioPauloFidel/Sistema-de-controle-de-gastos-residenciais) | .NET 8 · EF Core · SQLite · React + TypeScript |
| [Login com testes E2E](https://github.com/AntonioPauloFidel/login-e2e-cypress) | Node · SQLite · **Cypress** |
| [Cadastro e autenticação](https://github.com/AntonioPauloFidel/cadastro-autenticacao) | React · Node · SQLite · deploy no Railway |
| [Gestão de processos judiciais](https://github.com/AntonioPauloFidel/gestao-processos-judiciais-django) | Django · modelagem relacional |
| [FidelCine](https://github.com/AntonioPauloFidel/FidelCine) | React 19 · Vite · Context API |

---

## 🛠️ Tecnologias

**Back-end**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white"/> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/> <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white"/>

**Front-end e mobile**<br/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white"/>

**Dados**<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/> <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>

**IA aplicada**<br/>
<img src="https://img.shields.io/badge/RAG_e_embeddings-6E40C9?style=flat-square"/> <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/> <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square"/> <img src="https://img.shields.io/badge/Tesseract_OCR-5A5A5A?style=flat-square"/>

**DevOps e infraestrutura**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/> <img src="https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white"/> <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Zabbix-CC0000?style=flat-square&logo=zabbix&logoColor=white"/>

**Testes e qualidade**<br/>
<img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white"/> <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/> <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/> <img src="https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white"/>

**Metodologias**<br/>
<img src="https://img.shields.io/badge/Scrum-62498A?style=flat-square"/> <img src="https://img.shields.io/badge/Kanban-0077B5?style=flat-square"/> <img src="https://img.shields.io/badge/Conventional_Commits-FE5196?style=flat-square&logo=conventionalcommits&logoColor=white"/>
