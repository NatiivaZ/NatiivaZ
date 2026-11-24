<div align="center">

# Olá, eu sou o Ruan Natividade 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=640&lines=Analista+de+Dados+e+Automa%C3%A7%C3%A3o;Python+%C2%B7+TypeScript+%C2%B7+SQL;RPA+%C2%B7+Integra%C3%A7%C3%A3o+de+APIs+%C2%B7+Dashboards;CCOBI%2FANTT+%C2%B7+Bras%C3%ADlia%2FDF" alt="Analista de Dados e Automação · Python · TypeScript · SQL" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D&logoColor=white)](https://www.linkedin.com/in/ruan-natividade)
[![Portfólio](https://img.shields.io/badge/Portf%C3%B3lio-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://natiivaz.github.io/)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ruan.natividade1@icloud.com)

</div>

---

## Sobre mim

Trabalho com **análise de dados** e **automação de processos** na CCOBI (ANTT), na frente de cobrança: SERASA, CADIN, PEFIN e SIFAMA.

Meu trabalho é pegar rotinas que dependiam de planilhas e cliques manuais e transformar em ferramentas que a equipe usa no dia a dia, com status, histórico e exportação.

- 📊 Cruzamento e qualidade de bases (SERASA × Dívida Ativa)
- 🤖 Automação de portais (RPA) para inclusões, baixas e assinaturas em lote
- 🔌 Integração com APIs: filas, rate limit e webhooks
- 📈 Painéis em Streamlit e Next.js para acompanhamento operacional

---

## ⭐ Projeto em destaque

### [Negativador PEFIN · Plataforma de automação em massa](https://github.com/NatiivaZ/ccobi-api-serasa-pefin)

A API do credor não aceita envio em lote. A plataforma recebe uma planilha, valida cada registro e dispara as inclusões e exclusões uma a uma, sem estourar os limites da API.

- Fila assíncrona com **workers concorrentes** e **rate limit** configurável
- **6 webhooks** para confirmação assíncrona do credor
- **Dashboard em tempo real** com progresso por lote, reprocessamento de erros e exportação em Excel
- Ambientes de **homologação e produção** separados, API documentada em **Swagger/OpenAPI**

`TypeScript` `NestJS` `Prisma` `Next.js` `React` `Tailwind` `Recharts`

---

## 🗂️ Outros projetos

### Análise de bases

| Projeto | O que resolve | Stack |
|---|---|---|
| [Comparador SERASA × Dívida Ativa](https://github.com/NatiivaZ/ccobi-sistema-comparacao-serasa) | Cruza as duas bases e aponta divergências, com métricas, gráficos e exportação | Python · Streamlit · Plotly · SQLite |
| [Acompanhamento de vencimentos](https://github.com/NatiivaZ/ccobi-filtro-vencimento-divida) | Compara bases por ano de vencimento e guarda o histórico das execuções | Python · Streamlit · Plotly · SQLite |
| [Reclassificador de exportações SERASA](https://github.com/NatiivaZ/ccobi-reclassificador-exportacoes-serasa) | Reorganiza e reclassifica as exportações do SERASA | Python · Streamlit · Pandas |

### Automação de portais (RPA)

| Projeto | O que resolve | Stack |
|---|---|---|
| [Inclusão CADIN em lote](https://github.com/NatiivaZ/ccobi-inclusao-cadin) | Inclui registros no CADIN (PGFN) a partir de uma planilha | Python · nodriver · Pandas |
| [Baixas jurídicas CADIN](https://github.com/NatiivaZ/ccobi-baixas-cadin) | Executa baixas no CADIN Consulta Credora | Python · nodriver · Pandas |
| [Inscrição SERASA via SIFAMA](https://github.com/NatiivaZ/ccobi-inscricao-serasa) | Automatiza a inscrição de devedores no SERASA pelo SIFAMA | Python · Selenium · Pandas |
| [Baixas no portal SERASA](https://github.com/NatiivaZ/ccobi-baixas-serasa) | Processa baixas no portal SERASA Experian | Python · Selenium · Pandas |
| [Assinatura de lotes no SIFAMA](https://github.com/NatiivaZ/ccobi-assinatura-lotes-sifama) | Assina lotes de publicação no DOU sem intervenção manual | Python · Selenium |

### Utilitários

| Projeto | O que resolve | Stack |
|---|---|---|
| [Contagem de cartas SERASA](https://github.com/NatiivaZ/ccobi-contagem-cartas-serasa) | Conta as cartas SERASA a partir da planilha de autos | Python · Pandas |
| [Conversor REGATI/PEFIN](https://github.com/NatiivaZ/ccobi-conversor-txt-xlsx) | Converte arquivos TXT de retorno em planilhas Excel | Python · XlsxWriter |

> Os projetos CCOBI estão publicados como portfólio, sem credenciais, URLs internas ou dados reais. Cada repositório traz um `NOTICE.md` com os termos de uso e as regras de LGPD.

---

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,nodejs,nestjs,nextjs,react,tailwind,prisma,postgres,sqlite,selenium,git,github,vscode&perline=8" alt="Python, TypeScript, JavaScript, Node.js, NestJS, Next.js, React, Tailwind, Prisma, PostgreSQL, SQLite, Selenium, Git, GitHub, VS Code" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel" />
</p>

---

## 📬 Contato

Aberto a oportunidades em **análise de dados**, **automação/RPA** e **desenvolvimento de software**.

[LinkedIn](https://www.linkedin.com/in/ruan-natividade) · [Portfólio](https://natiivaz.github.io/) · [ruan.natividade1@icloud.com](mailto:ruan.natividade1@icloud.com)

<div align="center">

<sub><i>Dados com clareza. Processos com rastreabilidade. Ferramentas que a equipe usa.</i></sub>

</div>
