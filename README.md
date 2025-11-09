# Olá, eu sou Alessandro Pablo! 👋

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/PabloZed?style=social)](https://github.com/PabloZed)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-pablo-gon%C3%A7alves-de-andrade-54099484/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pablozed@gmail.com)

</div>

## 👨‍💻 Sobre Mim

Desenvolvedor Full-Stack apaixonado por criar soluções robustas, inteligentes e escaláveis. Meu foco é construir sistemas completos, desde a arquitetura do backend até a experiência do usuário no frontend, com um interesse especial em inteligência artificial e automação.

---

## 🚀 Meu Destaque Recente: Sistema de Gestão de Documentos com OCR Inteligente

Atualmente, estou trabalhando em um sistema completo de gerenciamento de documentos que demonstra a aplicação de diversas tecnologias modernas e boas práticas de engenharia de software.

**O que ele faz?**  
É uma plataforma full-stack containerizada que não apenas armazena e gerencia documentos de forma hierárquica, mas também utiliza um **serviço de OCR com treinamento "Human-in-the-Loop"**. Isso significa que o sistema aprende com as correções dos usuários para extrair automaticamente metadados (como títulos e códigos) de novos documentos, tornando-se mais inteligente a cada uso.

**Arquitetura e Tecnologias Utilizadas:**

| Categoria      | Tecnologias                                                                                             |
| -------------- | ------------------------------------------------------------------------------------------------------- |
| **Backend**    | Python, Django, Django REST Framework, PostgreSQL, Celery, Redis                                        |
| **Frontend**   | React, Material-UI (MUI), Axios, React Router                                                           |
| **IA & OCR**   | PyTesseract, Scikit-learn, Flask, Python (microserviço de OCR)                                          |
| **DevOps**     | Docker, Docker Compose (containerização completa do ambiente)                                           |
| **Protocolos** | RESTful APIs, WebSockets (Django Channels - notificações em tempo real)                                 |

> *💼 Este projeto está em desenvolvimento em repositório privado. Entre em contato para mais detalhes.*

---

## 📂 Projetos em Destaque

### [AppAgendas.com](https://appagendas.com) - Sistema SaaS Enterprise de Gestão de Agendamentos 🚀

<div align="left">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React_18-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Machine Learning](https://img.shields.io/badge/ML-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em_Produ%C3%A7%C3%A3o-success?style=flat)
![Commits](https://img.shields.io/badge/Commits-223-blue?style=flat)

</div>

**Plataforma completa de gestão empresarial** com CRM inteligente, Machine Learning e automação para estabelecimentos de serviços. Sistema multi-tenant que atende 12+ segmentos (salões, clínicas, academias, consultorias, etc.).

#### 🎯 Principais Funcionalidades

- **🤖 CRM Inteligente com ML**: Previsão de churn com RandomForest (85%+ precisão), segmentação RFM automática, recuperação de clientes em risco
- **📅 Agendamento 24/7**: Agendamentos recorrentes, sincronização com Google Calendar/Outlook, lembretes automáticos via WhatsApp/Email
- **🏪 Frontdesk & PDV**: Fila inteligente para walk-ins, check-in via QR Code, múltiplas formas de pagamento (Mercado Pago, Stripe)
- **🎮 Gamificação**: 12+ tipos de conquistas, 5 níveis de fidelidade (Bronze→Diamante), sistema de pontos e recompensas
- **📊 Analytics Avançado**: Dashboards especializados por perfil (Admin/Dono/Profissional/Cliente), KPIs em tempo real
- **💳 Pagamentos Integrados**: 4 planos de assinatura, pagamentos recorrentes, split automático, controle de comissões
- **📦 Gestão de Estoque**: Baixa automática de insumos, notificações de estoque baixo, controle de fornecedores
- **🔗 Integrações**: WhatsApp Evolution API (anti-ban), Calendários externos, Twilio SMS, Firebase Push

#### ⚡ Arquitetura & Tecnologias

| Categoria | Stack |
|-----------|-------|
| **Frontend** | React 18 + TypeScript + Vite, Tailwind CSS, i18next, PWA Offline-First |
| **Backend** | Django 5 + DRF, 30+ apps modulares, Celery + Redis, Django Channels (WebSocket) |
| **Database** | PostgreSQL + Redis (cache), Django ORM |
| **ML & IA** | Scikit-learn, LightGBM, RandomForest (Churn Prediction), NLP com Transformers |
| **Integrações** | Mercado Pago, Stripe, WhatsApp API, Twilio, Google Calendar API |
| **DevOps** | Docker Compose, Gunicorn + Nginx, VPS Contabo (217.216.65.246) |
| **Segurança** | JWT + OAuth2, Rate Limiting, AES-256, Conformidade LGPD, SSL/TLS |

#### 📊 Estatísticas do Projeto

- **~149k linhas de código** em 793 arquivos
- **223 commits** em desenvolvimento contínuo
- **30+ apps Django** modulares e reutilizáveis
- **90-95% implementado**, em produção com usuários reais
- **12 segmentos de mercado** atendidos

#### 🏆 Diferenciais Técnicos

✅ Machine Learning real (não é fake ML) - RandomForest para predição de churn
✅ Arquitetura modular enterprise-ready com 30+ Django apps independentes
✅ Anti-ban inteligente para WhatsApp com rate limiting e opt-in/opt-out
✅ Internacionalização completa (i18n) no frontend (i18next) e backend (django-parler)
✅ PWA com estratégia offline-first e Service Workers
✅ Type safety com TypeScript strict mode
✅ Testes robustos: Jest + Cypress (E2E) + Django TestCase
✅ Documentação OpenAPI automática com drf-spectacular

> 🌐 **Em produção:** [appagendas.com](https://appagendas.com) | [appagendas.com.br](https://appagendas.com.br)

---

### [Flight Search POC](https://github.com/PabloZed/flightSearchPOC)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)

Prova de conceito de sistema de busca de voos desenvolvido em Java 8 puro. Este projeto demonstra a aplicação de conceitos de programação funcional e streams do Java 8 para processamento eficiente de dados de voos.

**Tecnologias:** Java 8, Programação Funcional, Streams API

---

## 🛠️ Tecnologias e Ferramentas

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

### Stack Completo

- **Linguagens:** Python, JavaScript, TypeScript, Java, SQL
- **Backend:** Django 5, Django REST Framework, Flask, Node.js, Celery, Django Channels
- **Frontend:** React 18, TypeScript, Material-UI, Tailwind CSS, Vite, HTML5, CSS3
- **Bancos de Dados:** PostgreSQL, Redis, SQLite
- **IA & Machine Learning:** Scikit-learn, RandomForest, LightGBM, PyTesseract, Transformers, NLP
- **Integrações:** Mercado Pago, Stripe, WhatsApp API, Twilio, Google Calendar API
- **DevOps & Ferramentas:** Docker, Docker Compose, Gunicorn, Nginx, Git, REST APIs, Linux

---

## 🎯 O que estou buscando

- 🔹 Oportunidades em **desenvolvimento full-stack**
- 🔹 Projetos envolvendo **IA e automação**
- 🔹 Colaborações em **projetos open source**
- 🔹 Desafios técnicos que envolvam **arquitetura de sistemas escaláveis**

---

## 📫 Contato

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-pablo-gon%C3%A7alves-de-andrade-54099484/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pablozed@gmail.com)

</div>

---

## 📊 Estatísticas do GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=PabloZed&show_icons=true&theme=radical&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PabloZed&layout=compact&theme=radical&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=PabloZed&theme=radical)

</div>

---

<div align="center">
  <i>💡 "A melhor forma de prever o futuro é inventá-lo" - Alan Kay</i>
</div>
