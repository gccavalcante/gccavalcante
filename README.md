<div align="center">
  <img src="./assets/banner-perfil.svg" width="100%" alt="Gabriel Chaves do Carmo Cavalcante — Desenvolvedor Full-Stack Júnior e Analista de Dados Júnior" />

  <br />

  <p>
    <a href="https://www.linkedin.com/in/gabriel-chaves-/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Gabriel_Chaves-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Gabriel Chaves" />
    </a>
    <a href="mailto:gabrielccavalcante@gmail.com">
      <img src="https://img.shields.io/badge/E--mail-gabrielccavalcante%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail gabrielccavalcante@gmail.com" />
    </a>
    <a href="https://tads-store-gccavalcante.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/Live_Demo-NexusTech_Store-05D55A?style=for-the-badge&logo=vercel&logoColor=04150B" alt="Demonstração NexusTech Store na Vercel" />
    </a>
    <img src="https://img.shields.io/badge/Localiza%C3%A7%C3%A3o-Rio_de_Janeiro%2C_RJ-1E293B?style=for-the-badge&logo=googlemaps&logoColor=38BDF8" alt="Localização: Rio de Janeiro, RJ" />
    <img src="https://img.shields.io/badge/Ingl%C3%AAs-Fluente_(C2)-0F2922?style=for-the-badge&logoColor=6EE7B7" alt="Inglês Fluente C2" />
  </p>
</div>

---

## 👨‍💻 Resumo Profissional

Sou **Desenvolvedor Full-Stack** e graduando em **Tecnologia em Análise e Desenvolvimento de Sistemas pelo IFES** (`2025 – 2028`), com experiência prática no desenvolvimento e na refatoração de aplicações web institucionais, APIs RESTful, modelagem de bancos de dados relacionais e automação de processos utilizando **TypeScript, Node.js, Python (Django), React e SQL (PostgreSQL, MySQL e SQLite)**.

Atuo na interseção entre **Engenharia de Software** e **Análise de Dados**: construo sistemas desacoplados sob **Clean Architecture** e conteinerizados com **Docker**, ao mesmo tempo em que estruturo consultas indexadas, pipelines de ingestão/limpeza de dados e automações que reduzem trabalho manual e apoiam a tomada de decisão.

<div align="center">
  <img src="./assets/resumo-competencias.svg" width="100%" alt="Pilares de atuação: Engenharia de Software Full-Stack e Análise de Dados" />
</div>

---

## 💼 Experiência Profissional

### 🏛️ Residente em TIC — Desenvolvedor Full-Stack (`Editais.GOV`)
**Aponti / Softex / MCTI** · *Abr 2026 – Jun 2026* · *Rio de Janeiro, RJ*
- **Desenvolvimento & Refatoração Full-Stack:** Desenvolvi e refatorei módulos da plataforma institucional **Editais.GOV** para a **Prefeitura de Niterói/RJ**, utilizando **Python, Django e Wagtail CMS**.
- **Indexação de Dados & Automação de Processos:** Automatizei a organização estruturada de diretórios e documentos com **Django Signals** e implementei buscas avançadas e indexadas utilizando **Q Objects**, reduzindo operações manuais e acelerando a recuperação de informações públicas.
- **Segurança & Infraestrutura (DevOps):** Implementei políticas de **rate limiting** para proteção contra sobrecarga/abuso de requisições e conteinerizei o ecossistema com **Docker**, garantindo paridade entre ambientes de desenvolvimento e produção.

### 🚀 Formação em Desenvolvimento de Software — Bolsa Futuro Digital (240h)
**Aponti / Softex / MCTI** · *Ago 2025 – Jan 2026*
- Formação prática intensiva de 6 meses em Engenharia de Software, bancos de dados relacionais (**MySQL**) e arquitetura de sistemas.
- Desenvolvimento do projeto integrador final **SIRH (Sistema Integrador de Recursos Humanos)**: uma API RESTful corporativa em **TypeScript e Node.js** estruturada com **Clean Architecture**, validação com **Zod**, autenticação **JWT/BCrypt** e suíte de testes unitários com **Jest**.

---

## 📂 Projetos em Destaque

### 1. Engenharia de Software, APIs & Aplicações Web

| Projeto | Contexto & Arquitetura Técnica | Stack & Links |
| :--- | :--- | :--- |
| **[SIRH — API RESTful de Gestão de Contratos e RH](https://github.com/gccavalcante/projeto-integrador)** | API RESTful corporativa centralizando o ciclo de vida de clientes, serviços e contratos (`ACTIVE`, `PENDING`, `CANCELED`). Arquitetura em camadas (**Clean Architecture**: *Domain, Services/Use Cases, Adapters, Controllers*), autenticação **JWT + BCrypt**, validação de schemas com **Zod**, persistência em **MySQL** (`mysql2/promise`) e testes unitários com **Jest (`ts-jest`)** e **Biome**. | `TypeScript` `Node.js` `Express` `MySQL` `Clean Architecture` `JWT` `Zod` `Jest`<br>🔗 [Repositório API](https://github.com/gccavalcante/projeto-integrador) · [Schema SQL (`gestaorh.sql`)](https://github.com/gccavalcante/projeto-integrador/blob/main/gestaorh.sql) · [Front-end Angular](https://github.com/gccavalcante/projeto-integrador-front) |
| **[NexusTech Store — E-commerce SPA](https://github.com/gccavalcante/tads-store)** | Single Page Application simulando a jornada completa de e-commerce (catálogo com filtros dinâmicos e contadores, página técnica de produto com galeria e avaliações, carrinho reativo e checkout). Consumo assíncrono paralelo (`Promise.all`) da **DummyJSON API** e preenchimento automático de endereço via **ViaCEP**, estado global com **Context API** (`Auth`, `Carrinho`, `Favoritos`), persistência resiliente em `localStorage` e **Design System** próprio ([`DESIGN.md`](https://github.com/gccavalcante/tads-store/blob/main/DESIGN.md)). | `React 19` `Vite` `React Router v7` `Context API` `REST APIs` `CSS Tokens`<br>🔗 [Repositório GitHub](https://github.com/gccavalcante/tads-store) · [🚀 Live Demo (Vercel)](https://tads-store-gccavalcante.vercel.app/) · [Design System](https://github.com/gccavalcante/tads-store/blob/main/DESIGN.md) |
| **[Editais.GOV — Plataforma Institucional](https://github.com/gccavalcante)** *(Residência TIC)* | Evolução funcional e arquitetural de portal governamental para gestão e transparência de editais públicos da Prefeitura de Niterói/RJ, com foco em busca indexada, automação de diretórios via eventos e segurança de borda. | `Python` `Django` `Wagtail CMS` `Q Objects` `Signals` `Docker` |

---

### 2. Análise de Dados, SQL & Automação

Competências analíticas aplicadas em projetos e estrutura preparada para novos estudos de caso de **Data Analytics & BI**:

| Frente Analítica | Aplicação Prática & Escopo Técnico | Tecnologias |
| :--- | :--- | :--- |
| **[Modelagem Relacional & Consultas SQL](https://github.com/gccavalcante/Bolsa-Futuro-Digital)** | Modelagem de entidades, relacionamentos, constraints de integridade (chaves primárias/estrangeiras, unicidade de CNPJ/códigos), consultas com `JOIN`, filtros compostos, agregações e scripts DDL/DML aplicáveis a **MySQL**, **PostgreSQL** e **SQLite**. | `SQL` `MySQL` `PostgreSQL` `SQLite` `Modelagem Relacional`<br>🔗 [Scripts SQL & Práticas](https://github.com/gccavalcante/Bolsa-Futuro-Digital) · [Schema SIRH](https://github.com/gccavalcante/projeto-integrador/blob/main/gestaorh.sql) |
| **Automação, Ingestão & Busca Indexada em Python** | Tratamento e transformação de payloads JSON de múltiplas APIs, automação de fluxos operacionais com **Python / Django Signals**, consultas complexas via ORM (`Q Objects`) e exploração inicial de bases tabulares (`CSV`/`XLSX`) com Python e **Power Query**. | `Python` `Django ORM` `Power Query` `JSON / REST` `ETL` |
| **📌 Roadmap de Portfólio de Dados *(Em Preparação)*** | Novos estudos de caso em fase de estruturação e publicação:<br>• **Pipeline ETL & Análise Exploratória (EDA):** Ingestão, tratamento, validação de qualidade e análise estatística de bases públicas com **Python (Pandas)** e **PostgreSQL**.<br>• **Modelagem Dimensional & Dashboard de Negócios:** Construção de indicadores executivos (KPIs de vendas, retenção e operações) com **SQL**, **Power Query / Power BI** e documentação de insights. | `Python` `Pandas` `PostgreSQL` `Power Query` `Data Analytics` |

---

## 🛠️ Habilidades Técnicas & Ferramentas (ATS Matrix)

| Domínio | Tecnologias, Frameworks & Competências |
| :--- | :--- |
| **Linguagens de Programação & Consulta** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Back-end & Engenharia de APIs** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Wagtail](https://img.shields.io/badge/Wagtail_CMS-43B1B0?style=flat-square&logo=wagtail&logoColor=white) ![REST API](https://img.shields.io/badge/RESTful_APIs-02569B?style=flat-square) ![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) |
| **Front-end & UI Engineering** | ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white) ![Design Systems](https://img.shields.io/badge/Design_Systems_&_WCAG-10B981?style=flat-square) |
| **Bancos de Dados, BI & Analytics** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Power Query](https://img.shields.io/badge/Power_Query_&_ETL-F2C811?style=flat-square&logoColor=black) ![Modelagem de Dados](https://img.shields.io/badge/Modelagem_Relacional-0F766E?style=flat-square) |
| **Arquitetura, Qualidade & DevOps** | ![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-1E293B?style=flat-square) ![MVC](https://img.shields.io/badge/Arquitetura_MVC-1E293B?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS_(Fundamentos)-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Jest](https://img.shields.io/badge/Jest_(Testes_Unit%C3%A1rios)-C21325?style=flat-square&logo=jest&logoColor=white) ![Git](https://img.shields.io/badge/Git_&_GitHub-F05032?style=flat-square&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

---

## 🎓 Educação, Formação Complementar & Idiomas

- 🎓 **Tecnologia em Análise e Desenvolvimento de Sistemas (TADS)** — *Instituto Federal do Espírito Santo (IFES)* · `Jun 2025 – Jun 2028 (em andamento)`
- 💻 **Residência em TIC — Desenvolvimento Full-Stack (Python/Django & Docker)** — *Aponti / Softex / MCTI* · `Abr 2026 – Jun 2026`
- 🛠️ **Formação em Desenvolvimento de Software (240 horas)** — *Bolsa Futuro Digital (Aponti / Softex / MCTI)* · `Ago 2025 – Jan 2026`
- 📈 **Trilha Contínua em Dados, SQL & Cloud** — *Aperfeiçoamento em Análise de Dados com Python, Modelagem SQL, Power Query e fundamentos de AWS*
- 🌍 **Idiomas:**
  - **Português:** Nativo
  - **Inglês:** Fluente (**Nível C2 — Proficiência**)
  - **Espanhol:** Intermediário
  - **Francês:** Básico

---

## 📊 Indicadores de Perfil

<div align="center">
  <img src="./assets/indicadores-perfil.svg" width="100%" alt="Indicadores: GovTech/TIC Editais.GOV, ADS IFES + 240h Softex/MCTI, Clean Architecture e Inglês C2" />
</div>

---

## 🤝 Contato & Disponibilidade

Estou aberto a oportunidades como:
- **Desenvolvedor Full-Stack Júnior** | **Engenheiro de Software Júnior** | **Desenvolvedor Back-end Júnior** (`TypeScript / Node.js / Python / Django / React`)
- **Analista de Dados Júnior** | **BI & Analytics Júnior** (`SQL / Python / PostgreSQL / MySQL / ETL`)

📍 **Rio de Janeiro, RJ** *(Disponível para atuação Remota, Híbrida ou Presencial)*

- 💼 **LinkedIn:** [linkedin.com/in/gabriel-chaves-](https://www.linkedin.com/in/gabriel-chaves-/)
- ✉️ **E-mail:** [gabrielccavalcante@gmail.com](mailto:gabrielccavalcante@gmail.com)
- 🌐 **Portfólio (NexusTech Live):** [tads-store-gccavalcante.vercel.app](https://tads-store-gccavalcante.vercel.app/)
