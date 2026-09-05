<h1 align="center">Ramon Marsal</h1>

<p align="center">
  <strong>Segurança Ofensiva &nbsp;·&nbsp; Red Team &amp; Pentest &nbsp;·&nbsp; Infraestrutura &nbsp;·&nbsp; LLMSec</strong>
  <br>
  Brasília/DF — Brasil
</p>

<p align="center">
  <a href="https://0xetern4lw0lf.com">Portfólio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/ramonmarsal">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:ramonmarsal1997@gmail.com">E-mail</a>
</p>

---

Atuo desde 2021 com operações de Red Team e testes de intrusão avançados em ambientes
corporativos complexos: simulação realista de ameaças, comprometimento controlado de
infraestrutura e avaliação de maturidade defensiva.

Trabalho com invasão de ambientes Windows (Active Directory) e Linux, aplicando
pós-exploração, movimentação lateral, evasão de defesas (AV/EDR) e persistência. A base
em infraestrutura, virtualização e administração de sistemas permite atuação de ponta a
ponta — do reconhecimento ao domínio do ambiente.

Frente atual: **segurança aplicada a IA (LLMSec)** — análise de vulnerabilidades em LLMs,
mitigação de Prompt Injection, orquestração de agentes autônomos e operação de modelos
locais em hardware dedicado.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox VE">
  <img src="https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white" alt="pfSense">
  <img src="https://img.shields.io/badge/Elastic_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white" alt="Elastic Stack">
</p>

---

## Competências Técnicas

**Segurança Ofensiva**
Active Directory · Reconhecimento e enumeração · Escalada de privilégios · Movimentação
lateral · Pós-exploração · Evasão de defesas (AV/EDR) · Testes de intrusão · Análise de
vulnerabilidades · OSINT e inteligência cibernética

**Ferramentas Ofensivas**
Nmap · Metasploit · Burp Suite · BloodHound · Cobalt Strike · Sliver

**Inteligência Artificial & LLMs**
Engenharia de prompts · Orquestração de agentes autônomos · Integração de ferramentas via
MCP (Model Context Protocol) · Execução de modelos locais (SLMs/LLMs) em hardware dedicado

**Segurança em IA (LLMSec)**
Análise de vulnerabilidades em LLMs · Mitigação de Prompt Injection (direta e indireta) ·
Segurança defensiva com suporte de IA

**Infraestrutura & Redes**
Administração de servidores Linux e Windows · Proxmox VE · Ceph · pfSense · Docker e
ambientes virtualizados · VPNs · Monitoramento e gestão de logs (Zabbix, Elastic Stack)

**Automação & Programação**
Python · Bash · Automação de workflows (n8n) · Integração de APIs · Java (conceitos
básicos/estruturais)

---

## Projetos em Destaque

### Konhecia — RAG corporativo 100% on-premise

**Problema.** Assistentes corporativos apoiados em LLMs comerciais exigem enviar documentos
internos a APIs de terceiros, o que é inviável sob requisitos de confidencialidade. Somado a
isso, sistemas de RAG tendem a responder mesmo quando a base não cobre a pergunta.

**Solução.** API de perguntas e respostas sobre documentos internos com LLM e embeddings
executados inteiramente no ambiente do cliente, via Ollama — nenhum dado sai da
infraestrutura. Ingestão de PDFs com chunking e indexação vetorial no Qdrant, histórico de
sessões em PostgreSQL, respostas em streaming (SSE) e autenticação por API key. O controle de
alucinação é explícito: trechos abaixo do score mínimo de relevância são descartados e o
agente recusa a resposta em vez de inventá-la. Persona parametrizável por domínio de suporte.

**Stack.** Python · FastAPI · Pydantic v2 · LangChain · Qdrant · Ollama (`qwen2.5:7b`,
`nomic-embed-text`) · PostgreSQL com SQLAlchemy async e Alembic · Docker Compose · pytest

**Repositório.** https://github.com/0xEtern4lW0lf/konhecia

### Em desenvolvimento

- **[voxscale](https://github.com/0xEtern4lW0lf/voxscale)** — pipeline de análise de
  sentimento em escala com aceleração por GPU: PyTorch/CUDA, DistilBERT multilíngue,
  Polars/PyArrow e PostgreSQL, com geração de dataset sintético e benchmark CPU vs GPU.
  *Estágio: estrutura base (configuração, persistência e telemetria); pipeline em construção.*

- **[aemulus](https://github.com/0xEtern4lW0lf/aemulus)** — sistema multiagente autônomo
  para inteligência competitiva, com LangGraph, modelo local via Ollama e coleta web
  (DuckDuckGo + trafilatura). *Estágio: scaffold — Fase 1.*

---

## Atuação Atual

- Segurança de IA (LLMSec): análise de vulnerabilidades em LLMs e mitigação de ataques de
  Prompt Injection, diretos e indiretos.
- Orquestração de agentes autônomos e integração de ferramentas via MCP
  (Model Context Protocol).
- Deploy e operação de modelos de linguagem locais (SLMs/LLMs) em hardware dedicado
  (clusters GPU), aplicados a inferência e automação de tarefas.
- Desenvolvimento de automações de workflow com n8n, Python e integração de APIs para
  operações de segurança.
- Criação e manutenção de laboratórios dedicados a simulações Red Team / Blue Team.

<img src="https://tryhackme-badges.s3.amazonaws.com/smithbenison.png" alt="TryHackMe">

---

## Certificações

| Certificação | Emissor | Ano |
| --- | --- | :---: |
| Solyd Certified Pentester (SYCP) | Solyd | 2023 |
| Tratamento de Incidentes de Segurança | RNP / ESR | 2023 |
| Offensive Security Experienced Penetration Tester (OSEP) | Offensive Security | 2022 |
| Desec Certified Penetration Tester (DCPT) | Desec Security | 2022 |

---

## Formação

- **Tecnólogo em Segurança da Informação** — Faculdade UniFatecie *(em conclusão)*
- **Pós-Graduação em Ethical Hacking e Cybersecurity** — Faculdade VINCIT *(2023)*
- **Curso de Guerra Cibernética** *(2021)*
- **Tecnólogo em Gestão de Comunicações Militares** — Escola de Sargentos das Armas (ESA) *(2020)*

**Idiomas:** Português (nativo) · Inglês (leitura técnica)

---

## Contato

- **E-mail:** [ramonmarsal1997@gmail.com](mailto:ramonmarsal1997@gmail.com)
- **LinkedIn:** [linkedin.com/in/ramonmarsal](https://www.linkedin.com/in/ramonmarsal)
- **Portfólio:** [0xetern4lw0lf.com](https://0xetern4lw0lf.com)
