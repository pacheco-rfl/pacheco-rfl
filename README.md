# 👨‍💻 Rafael Pacheco

### Desenvolvedor Back-End | Java & Spring Boot | Estudante de Análise e Desenvolvimento de Sistemas

Sou estudante de desenvolvimento de software em **São Paulo, Brasil**, atualmente cursando **Análise e Desenvolvimento de Sistemas (ADS) no IFSP**.

Meu principal foco é **Desenvolvimento Back-End com Java, Spring Boot e IA**, com experiência prática na construção de APIs REST, integração com bancos de dados relacionais, autenticação e autorização, automação de processos e desenvolvimento de aplicações Full Stack.

Também concluí um curso de **Desenvolvimento Web no Instituto da Oportunidade Social (IOS)** e continuo aprimorando meus conhecimentos através de projetos práticos, estudos independentes e desenvolvimento contínuo.

Atualmente, estou aprofundando meus conhecimentos em:

- Java e Spring Boot;
- APIs REST;
- Spring Security;
- JWT e OAuth2;
- JPA e Hibernate;
- PostgreSQL;
- Docker;
- testes automatizados;
- CI/CD;
- arquitetura de software;
- integração entre sistemas;
- tecnologias em nuvem e AWS.

---

# 🚀 Projeto em Destaque

## Centraliza

**Plataforma Full Stack para gestão centralizada de processos operacionais.**

O **Centraliza** é um ecossistema completo desenvolvido para centralizar diferentes fluxos operacionais em uma única plataforma, reunindo frontend, backend, banco de dados, segurança, documentos e automação.

O projeto é dividido em três aplicações independentes:

```text
                    Centraliza Web
              React + TypeScript + Vite
                         │
                    REST / JWT
                         │
                         ▼
                    Centraliza API
                 Java + Spring Boot
                    /           \
                   /             \
                  ▼               ▼
           PostgreSQL        ProcessBuilder
                                  │
                                  ▼
                       Centraliza Automation
                         Python + Selenium
                                  │
                                  ▼
                         Ambiente Web Demo
```

### Principais funcionalidades

- autenticação com JWT;
- controle de acesso baseado em cargos e permissões;
- RBAC com permissões específicas;
- gerenciamento de usuários;
- gerenciamento de cargos;
- dashboard operacional;
- gerenciamento de Call Backs;
- acompanhamento de Lembretes;
- Remanejamentos de agendas;
- busca integrada de pacientes;
- histórico de tentativas de contato;
- auditoria e rastreabilidade;
- processamento de documentos;
- visualização de arquivos PDF;
- proteção de credenciais da automação;
- integração Java ↔ Python;
- automação de navegador com Selenium;
- acompanhamento de execução em tempo real;
- possibilidade de interromper uma automação;
- persistência com PostgreSQL;
- migrations com Flyway;
- documentação com OpenAPI / Swagger;
- testes automatizados;
- cobertura com JaCoCo;
- pipelines independentes com GitHub Actions.

### Arquitetura

```text
Usuário
  │
  ▼
React + TypeScript
  │
  │ REST / JSON + JWT
  ▼
Spring Boot API
  │
  ├──────────────► PostgreSQL
  │
  └── ProcessBuilder
          │
          ▼
        Python
          │
          ▼
       Selenium
          │
          ▼
   Ambiente Web Demo
```

### Repositórios

🔹 **Visão Geral do Projeto**  
https://github.com/pacheco-rfl/centraliza

🔹 **API Back-End**  
https://github.com/pacheco-rfl/centraliza-portfolio-api

🔹 **Front-End**  
https://github.com/pacheco-rfl/centraliza-portfolio-web

🔹 **Módulo de Automação**  
https://github.com/pacheco-rfl/centraliza-portfolio-automation

> A versão pública do projeto utiliza exclusivamente pacientes, profissionais, unidades, documentos, credenciais e ambientes fictícios para fins de demonstração.

---

# 🛠️ Tecnologias

## ⚙️ Back-End

<p align="left">
  <img alt="Java" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" />
  &nbsp;
  <img alt="Spring Boot" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" />
  &nbsp;
  <img alt="Python" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
</p>

`Java` · `Spring Boot` · `Spring Security` · `APIs REST` · `JWT` · `JPA` · `Hibernate` · `Maven`

---

## 🌐 Front-End

<p align="left">
  <img alt="React" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  &nbsp;
  <img alt="TypeScript" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" />
  &nbsp;
  <img alt="JavaScript" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
  &nbsp;
  <img alt="HTML5" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
  &nbsp;
  <img alt="CSS3" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" />
</p>

`React` · `TypeScript` · `Vite` · `React Router` · `HTML` · `CSS` · `JavaScript`

---

## 🗄️ Bancos de Dados

<p align="left">
  <img alt="PostgreSQL" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />
  &nbsp;
  <img alt="MySQL" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />
</p>

`PostgreSQL` · `MySQL` · `SQL` · `Flyway` · `Database Migrations`

---

## 🤖 Automação

<p align="left">
  <img alt="Python" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  &nbsp;
  <img alt="Selenium" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/selenium/selenium-original.svg" />
</p>

`Python` · `Selenium` · `WebDriver` · `Automação de Navegador` · `Integração Java/Python`

---

## 🔧 Ferramentas & DevOps

<p align="left">
  <img alt="Git" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
  &nbsp;
  <img alt="GitHub" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
  &nbsp;
  <img alt="Docker" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
  &nbsp;
  <img alt="Postman" width="45px" src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" />
  &nbsp;
  <img alt="AWS" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" />
</p>

`Git` · `GitHub` · `GitHub Actions` · `Docker` · `Postman` · `OpenAPI / Swagger` · `CI/CD` · `AWS`

---

# 🔐 Back-End & Segurança

Nos meus projetos, venho aplicando conceitos relacionados à construção de APIs seguras e organizadas.

Entre eles:

- desenvolvimento de APIs REST;
- autenticação com JWT;
- Spring Security;
- controle de acesso baseado em cargos;
- permissões específicas;
- proteção de endpoints;
- validação de requisições;
- tratamento global de exceções;
- hash de senhas;
- criptografia de informações sensíveis;
- migrations de banco de dados;
- auditoria;
- rastreabilidade de operações.

No Centraliza, a autorização não depende apenas do cargo do usuário.

Cada cargo possui permissões específicas que determinam quais operações podem ser realizadas.

Exemplo:

```text
Administrador
├── Gerenciar usuários
├── Gerenciar cargos
├── Gerenciar permissões
├── Configurar automação
├── Gerenciar Call Backs
├── Gerenciar Lembretes
└── Gerenciar Remanejamentos

Atendente
├── Visualizar Call Backs
├── Registrar contatos
├── Visualizar Lembretes
├── Registrar contatos em Lembretes
└── Registrar contatos em Remanejamentos
```

A interface utiliza essas permissões para controlar a experiência do usuário, enquanto a autorização definitiva é realizada pela API.

---

# 🤖 Automação & Integração de Sistemas

Também tenho experiência prática com integração entre aplicações desenvolvidas em tecnologias diferentes.

No Centraliza, a API Java inicia um processo Python responsável pela automação.

```text
Spring Boot
     │
     │ ProcessBuilder
     ▼
Python Runner
     │
     ▼
Selenium
     │
     ▼
Ambiente Web Demo
```

O processo Python envia informações de progresso de volta para a aplicação Java através de mensagens estruturadas na saída padrão (`stdout`).

Exemplo:

```text
[CENTRALIZA_PROGRESS]
```

O backend interpreta essas mensagens e disponibiliza o andamento para o frontend.

Isso permite acompanhar:

- status atual da execução;
- quantidade de registros processados;
- operações realizadas com sucesso;
- falhas;
- registros ignorados;
- item atualmente processado;
- percentual de progresso;
- horário de início;
- horário de finalização;
- código de saída da automação.

---

# 🧪 Testes & Qualidade de Código

Busco utilizar validações automatizadas para melhorar a confiabilidade e a manutenção das aplicações.

No Back-End do Centraliza, o projeto utiliza:

- testes automatizados;
- Maven Verify;
- JaCoCo;
- PostgreSQL durante a integração contínua;
- validação das migrations com Flyway.

Os três módulos possuem pipelines independentes no GitHub Actions.

```text
Frontend
npm ci
   ↓
npm run build
   ↓
Build validado


Backend
PostgreSQL
   ↓
Maven Verify
   ↓
Testes Automatizados
   ↓
JaCoCo
   ↓
Build validado


Automação
pip install
   ↓
Instalação das dependências
   ↓
Validação dos módulos Python
   ↓
Código validado
```

---

# 🏗️ Arquitetura & Engenharia

Alguns conceitos de engenharia de software aplicados nos meus projetos incluem:

- separação de responsabilidades;
- arquitetura em camadas;
- frontend e backend desacoplados;
- API REST como ponto central da aplicação;
- controle de acesso;
- migrations de banco;
- versionamento com Git;
- integração contínua;
- comunicação entre processos;
- tratamento centralizado de erros;
- auditoria;
- documentação de API;
- configuração através de variáveis de ambiente.

No Centraliza, frontend, backend e automação possuem repositórios independentes e responsabilidades específicas.

```text
Centraliza
│
├── Web
│   └── Interface e experiência do usuário
│
├── API
│   └── Segurança, regras de negócio e persistência
│
└── Automation
    └── Automação de navegador e processamento
```

---

# 📚 Atualmente Estudando

Atualmente estou aprofundando meus conhecimentos em Back-End através do curso:

### Spring Boot Expert: JPA, REST, JWT, OAuth2 com Docker e AWS

Meu foco atual de estudos inclui:

- Spring Boot avançado;
- boas práticas para APIs REST;
- Spring Security;
- JWT;
- OAuth2;
- autenticação e autorização;
- JPA;
- Hibernate;
- PostgreSQL;
- Docker;
- AWS;
- deploy em nuvem;
- testes automatizados;
- arquitetura de aplicações;
- aplicações Back-End escaláveis.

---

# 🎓 Formação

## Análise e Desenvolvimento de Sistemas — IFSP

Atualmente cursando **Análise e Desenvolvimento de Sistemas (ADS)**.

Áreas de maior interesse:

- desenvolvimento de software;
- desenvolvimento Back-End;
- bancos de dados;
- APIs;
- arquitetura de sistemas;
- engenharia de software.

---

## Desenvolvimento Web — Instituto da Oportunidade Social (IOS)

Curso concluído com foco nos fundamentos do desenvolvimento de aplicações web.

Durante o curso, tive contato com conceitos relacionados a:

- HTML;
- CSS;
- JavaScript;
- desenvolvimento de interfaces;
- lógica de programação;
- desenvolvimento web.

---

# 💡 Áreas de Interesse

Tenho interesse especial em trabalhar com:

```text
Java
Spring Boot
APIs REST
PostgreSQL
Spring Security
Arquitetura de Software
Integração de Sistemas
Automação de Processos
Docker
CI/CD
Cloud
AWS
```

---

# 🎯 Objetivo Profissional

Meu objetivo é crescer profissionalmente como **Desenvolvedor Back-End**, construindo aplicações confiáveis, organizadas, seguras e escaláveis, aplicando boas práticas de engenharia de software.

Tenho especial interesse em oportunidades envolvendo:

- Java e Spring Boot;
- desenvolvimento de APIs;
- bancos de dados relacionais;
- arquitetura de software;
- autenticação e segurança;
- integração entre sistemas;
- automação de processos;
- Docker;
- CI/CD;
- tecnologias em nuvem.

Apesar do meu foco profissional estar em Back-End, gosto de compreender o ciclo completo de uma aplicação.

Por isso, desenvolvo projetos que envolvem:

```text
Frontend
   +
Backend
   +
Banco de Dados
   +
Segurança
   +
Automação
   +
DevOps
```

---

# 📌 Projetos

## 🚀 Centraliza

Plataforma Full Stack com Java, Spring Boot, React, PostgreSQL, Python e Selenium.

🔗 https://github.com/pacheco-rfl/centraliza

---

### ⚙️ Centraliza API

API REST responsável pelas regras de negócio, autenticação, autorização, persistência, auditoria e integração com automação.

**Tecnologias:**

`Java` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `Flyway` · `JWT` · `JPA` · `Hibernate`

🔗 https://github.com/pacheco-rfl/centraliza-portfolio-api

---

### 🌐 Centraliza Web

Frontend responsável pela interface, dashboards, gerenciamento dos processos e acompanhamento da automação.

**Tecnologias:**

`React` · `TypeScript` · `Vite` · `React Router`

🔗 https://github.com/pacheco-rfl/centraliza-portfolio-web

---

### 🤖 Centraliza Automation

Módulo responsável pela execução da automação de navegador e integração com a API.

**Tecnologias:**

`Python` · `Selenium` · `WebDriver`

🔗 https://github.com/pacheco-rfl/centraliza-portfolio-automation

---

# 📫 Contato

📍 **São Paulo, Brasil**

💻 **GitHub**  
https://github.com/pacheco-rfl

💼 **LinkedIn**  
https://linkedin.com/in/rafael-pacheco-morais

📧 **E-mail**  
rafaelpacheco1324@yahoo.com

---

<p align="center">
  <b>Sempre aprendendo, construindo e evoluindo.</b>
</p>
