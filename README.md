<div align="center">

# Olá, eu sou o Daniel Martins 👋
### **Analista de TI & Desenvolvedor Full Stack | Automação com IA**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielmartins30)
[![Email](https://img.shields.io/badge/Email-danielmartins30%40icloud.com-EA4335?style=for-the-badge&logo=icloud&logoColor=white)](mailto:danielmartins30@icloud.com)
[![Inglês C1](https://img.shields.io/badge/Inglês-Avançado%20(C1)-059669?style=for-the-badge&logo=googletranslate&logoColor=white)](#)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=danmrtx&label=Visualiza%C3%A7%C3%B5es%20do%20Perfil&color=4f46e5&style=flat-square" alt="Visitas ao Perfil" />
</p>

---

</div>

## 👨‍💻 Sobre Mim

Sou graduando do **8º semestre de Sistemas de Informação** na Faculdade UniFTC e atuo como **Analista de T.I no Grupo Itadil**. Tenho sólida vivência em diagnóstico de falhas, infraestrutura, suporte a sistemas corporativos e otimização de processos com desenvolvimento de software e automação inteligente.

- 🔭 **Foco de Atuação:** Construção de aplicações web modernas, dashboards corporativos, arquiteturas escaláveis e automação de fluxos técnicos utilizando **IA Aplicada** e engenharia de prompts.
- 💼 **Experiência Profissional:** Vivência corporativa prática em ambientes dinâmicos de TI, alinhando suporte técnico de alto nível, visão de processos e criação de ferramentas sob medida.
- 🌐 **Idiomas:** Inglês Avançado (**C1** - apto para times e documentação internacional) e Espanhol Básico (**A2**).
- 🎯 **Diferenciais:** Perfil analítico, proativo, com visão comercial e forte habilidade na resolução de problemas complexos.

---

## 🚀 Projetos em Destaque

Aqui estão alguns dos principais sistemas desenvolvidos para resolver problemas reais de gestão, produtividade e auditoria corporativa:

---

### 1. 📦 [Nexus360 - Gestão Integrada de Estoque & WMS](https://github.com/danmrtx/nexus360)

> **Sistema corporativo moderno para gestão de estoques de alta rotatividade, controle de perdas e automação logística para redes de varejo e centros de distribuição.**

<div align="center">
  <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-preview.jpg" alt="Nexus360 Dashboard Preview" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);" />
</div>

- **O Problema Resolvido:** Redução drástica de prejuízos causados por produtos vencidos e gargalos de reposição entre filiais e matriz.
- **Destaques Técnicos:**
  - **Algoritmo FEFO (*First Expired, First Out*):** Automação na baixa e separação dos lotes com data de validade mais próxima, bloqueando produtos vencidos automaticamente.
  - **Arquitetura Multi-Unidades:** Gestão unificada de estoques em Centros de Distribuição (CDs) e Lojas com transferências e aprovações atômicas.
  - **Segurança Corporativa (RBAC + RLS):** Controle rigoroso de permissões com *Row Level Security* direto no banco PostgreSQL.
  - **Painel Analítico de KPIs:** Métricas em tempo real de capital imobilizado, estoques críticos e curva ABC.
- **Stack:** `Next.js 14`, `React`, `TypeScript`, `Tailwind CSS`, `Supabase (PostgreSQL / RLS)`.

👉 **[Acessar Repositório do Nexus360](https://github.com/danmrtx/nexus360)**

---

### 2. ⏱️ [UpperTime - Rastreador Inteligente de Horas Extras CLT](https://github.com/danmrtx/UpperTime)

> **Progressive Web App (PWA) para acompanhamento preciso de jornadas de trabalho, cálculo automático de minutos extras/atrasos e gestão de banco de horas.**

<div align="center">
  <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/uppertime-preview.jpg" alt="UpperTime Preview" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);" />
</div>

- **O Problema Resolvido:** Elimina surpresas e discrepâncias no fechamento mensal da folha de pagamento para colaboradores CLT e prestadores.
- **Destaques Técnicos:**
  - **Batida Instantânea com Delta:** Cálculo em tempo real de minutos positivos/negativos comparando a marcação real com a jornada configurada.
  - **Jornadas Flexíveis:** Suporte a horários personalizados para dias de semana, sábados e domingos.
  - **Instalação Nativa (PWA):** Funciona no navegador do celular (Android/iOS) e desktop sem necessidade de loja de aplicativos.
  - **Cloud Sync & Exportação:** Armazenamento individual criptografado na nuvem e exportação de históricos para planilhas Excel/CSV.
- **Stack:** `JavaScript (ES6+)`, `HTML5 & CSS3 Moderno`, `PWA / Service Workers`, `Vercel Serverless Functions`, `Supabase`.

👉 **[Acessar Repositório do UpperTime](https://github.com/danmrtx/UpperTime)**

---

### 3. 📄 [NotaFácil - Extrator de Danfe & Rateio Contábil de Notas Fiscais](https://github.com/danmrtx/NotaFacil)

> **Ferramenta client-side para processamento inteligente de PDFs de Danfe, fragmentação unitária de itens e geração de relatórios de rateio.**

<div align="center">
  <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/notafacil-preview.jpg" alt="NotaFácil Preview" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);" />
</div>

- **O Problema Resolvido:** Elimina o trabalho manual de contabilidade e TI de abrir notas fiscais com múltiplos itens e atribuir chamados e centros de custo unidade por unidade.
- **Destaques Técnicos:**
  - **100% Client-Side:** Leitura e extração de dados diretamente no navegador via JavaScript (zero custo de infraestrutura e privacidade total de dados fiscais).
  - **Fragmentação Inteligente de Itens:** Separa automaticamente itens com quantidades múltiplas em linhas individuais para rateio detalhado.
  - **Exportação Formatada:** Geração instantânea de relatório em PDF customizado com dados da empresa, número da NF, tickets e rateios atribuídos.
- **Stack:** `JavaScript`, `Tailwind CSS`, `PDF.js`, `jsPDF / AutoTable`.

👉 **[Acessar Repositório do NotaFácil](https://github.com/danmrtx/NotaFacil)**

---

## 🛠️ Tecnologias & Habilidades

<table>
  <tr>
    <td valign="top" width="25%">
      <h4>Frontend</h4>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /><br/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /><br/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <h4>Backend & Dados</h4>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <h4>IA & Automação</h4>
      <img src="https://img.shields.io/badge/Prompt_Engineering-8E75C4?style=flat-square&logo=openai&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/AI_Automation-FF6F00?style=flat-square&logo=google&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/LLM_Integration-412991?style=flat-square&logo=anthropic&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Process_Optimization-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <h4>Infra & Ferramentas</h4>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Suporte_Corporativo-4A154B?style=flat-square&logo=slack&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Redes_e_Hardware-232F3E?style=flat-square&logo=serverfault&logoColor=white" />
    </td>
  </tr>
</table>

---

## 📊 Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=danmrtx&show_icons=true&theme=tokyonight&locale=pt-br&hide_border=true&count_private=true" alt="Estatísticas de Daniel no GitHub" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=danmrtx&layout=compact&theme=tokyonight&locale=pt-br&hide_border=true" alt="Linguagens mais utilizadas" height="150" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=danmrtx&theme=tokyonight&hide_border=true" alt="Streak do GitHub" />
</div>

---

<div align="center">
  <sub>Desenvolvido com dedicação por <b>Daniel Martins</b> | Aberto a novos desafios e conexões profissionais</sub>
</div>
