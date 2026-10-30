<div align="center">

# Daniel Martins
### **Analista de TI & Desenvolvedor Full Stack | Automação com IA**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielmartins30)
[![Email](https://img.shields.io/badge/Email-danielmartins30%40icloud.com-EA4335?style=for-the-badge&logo=icloud&logoColor=white)](mailto:danielmartins30@icloud.com)
[![Inglês C1](https://img.shields.io/badge/Inglês-Avançado%20(C1)-059669?style=for-the-badge&logo=googletranslate&logoColor=white)](#)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=danmrtx&label=Visualizações%20do%20Perfil&color=4f46e5&style=flat-square" alt="Visitas ao Perfil" />
</p>

---

</div>

## Sobre Mim

Sou graduando do **8º semestre de Sistemas de Informação** na Faculdade UniFTC e atuo como **Analista de T.I no Grupo Itadil**. Possuo sólida experiência em infraestrutura corporativa, diagnóstico e resolução de falhas, suporte a sistemas críticos e otimização de fluxos operacionais por meio de desenvolvimento de software e inteligência artificial.

- **Foco de Atuação:** Construção de aplicações web robustas, dashboards analíticos para gestão, arquiteturas em nuvem e automação de processos corporativos com uso estratégico de IA e engenharia de prompts.
- **Experiência Corporativa:** Atuação direta em ambientes operacionais e corporativos de alta demanda, alinhando suporte técnico avançado, governança e desenvolvimento de ferramentas customizadas.
- **Idiomas:** Inglês Avançado (**C1** - apto para comunicação técnica e ambientes globais) e Espanhol Básico (**A2**).
- **Competências:** Pensamento analítico, perfil orientador de resultados, proatividade, relacionamento comercial e resolução estratégica de problemas.

---

## Projetos em Destaque

---

### 1. Nexus360 - Gestão Integrada de Estoque e WMS

> **Sistema corporativo moderno para gestão de estoques de alta rotatividade, controle de perdas e automação logística para redes de varejo e centros de distribuição.**

<div align="center">
  <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-dashboard.png" alt="Nexus360 - Painel Principal" width="100%" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12);" />
  <p><em>Painel Principal: KPIs operacionais em tempo real, produtos vencidos, estoques críticos e navegação integrada entre módulos.</em></p>
</div>

<br/>

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">Controle e Rastreabilidade de Lotes</h4>
      <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-lotes.png" alt="Controle de Lotes e Validades" width="100%" style="border-radius: 6px;" />
      <p align="center"><sub>Rastreabilidade ponta a ponta (Produto, NF, Lote, Validade e classificação de risco).</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">Entrada de Mercadorias</h4>
      <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-entradas.png" alt="Entrada de Mercadorias" width="100%" style="border-radius: 6px;" />
      <p align="center"><sub>Recebimento físico vinculado a Fornecedor, NF e geração instantânea de lote com validade.</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">Saída de Mercadorias (Algoritmo FEFO)</h4>
      <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-saidas-fefo.png" alt="Saída FEFO" width="100%" style="border-radius: 6px;" />
      <p align="center"><sub>Baixas inteligentes priorizando lotes de menor vencimento para erradicar perdas no varejo.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">Relatórios Gerenciais e Indicadores</h4>
      <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-relatorios.png" alt="Relatórios Gerenciais" width="100%" style="border-radius: 6px;" />
      <p align="center"><sub>Métricas analíticas de Curva ABC, taxa de ruptura, histórico de movimentações e cálculo de perdas.</sub></p>
    </td>
  </tr>
  <tr>
    <td colspan="2" width="100%" valign="top">
      <h4 align="center">Controle de Usuários e Permissões (RBAC)</h4>
      <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/nexus360-usuarios.png" alt="Controle de Usuários e Permissões" width="100%" style="border-radius: 6px;" />
      <p align="center"><sub>Gestão de acessos por perfil (Administrador, Gerente, Operador) e escopo de visualização por loja física ou matriz.</sub></p>
    </td>
  </tr>
</table>

- **Problema Solucionado:** Erradicação de prejuízos operacionais decorrentes de produtos vencidos nas gôndolas e otimização dos fluxos de reposição entre filiais e centros de distribuição.
- **Destaques Técnicos:**
  - **Algoritmo FEFO (First Expired, First Out):** Automação total nas baixas e separações priorizando os lotes mais próximos da data de expiração, com trava automática para lotes vencidos.
  - **Arquitetura Multi-Unidades:** Gestão unificada com segregação física entre Centros de Distribuição (CDs) e Lojas, com solicitações e transferências atômicas.
  - **Segurança Corporativa (RBAC + RLS):** Controle de permissões baseado em funções corporativas com *Row Level Security* nativo no PostgreSQL.
  - **Métricas Analíticas:** Painéis de curva ABC, cálculo de risco financeiro em estoque e sugestões automáticas de reposição.
- **Stack:** `Next.js 14`, `React`, `TypeScript`, `Tailwind CSS`, `Supabase (PostgreSQL / RLS)`.

[Repositório do Nexus360](https://github.com/danmrtx/nexus360)

---

### 2. UpperTime - Rastreador Inteligente de Horas Extras CLT

> **Progressive Web App (PWA) para acompanhamento preciso de jornadas de trabalho, cálculo automático de minutos extras/atrasos e gestão de banco de horas.**

<div align="center">
  <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/uppertime-preview.png" alt="UpperTime Preview" width="100%" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12);" />
</div>

- **Problema Solucionado:** Eliminação de divergências e falta de previsibilidade no fechamento mensal da folha de pagamento para profissionais em regime CLT e prestadores flexíveis.
- **Destaques Técnicos:**
  - **Batida Instantânea com Cálculo de Delta:** Apuração em tempo real de minutos adicionais ou atrasos em relação à escala de trabalho prevista.
  - **Configurações Individuais de Jornada:** Personalização completa de escalas diárias, incluindo diferenciação para sábados e domingos.
  - **Instalação Nativa (PWA):** Execução independente no navegador mobile (iOS e Android) ou desktop, operando com agilidade e design responsivo.
  - **Sincronização em Nuvem e Exportação:** Persistência segura em nuvem e exportação dos dados estruturados em formato CSV/Excel.
- **Stack:** `JavaScript (ES6+)`, `HTML5 & CSS3`, `PWA / Service Workers`, `Vercel Serverless Functions`, `Supabase`.

[Repositório do UpperTime](https://github.com/danmrtx/UpperTime)

---

### 3. NotaFácil - Extrator de Danfe e Rateio Contábil de Notas Fiscais

> **Ferramenta client-side para processamento inteligente de PDFs de Danfe, fragmentação unitária de itens e geração de relatórios de rateio.**

<div align="center">
  <img src="https://raw.githubusercontent.com/danmrtx/danmrtx/main/assets/notafacil-preview.png" alt="NotaFácil Preview" width="100%" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.12);" />
</div>

- **Problema Solucionado:** Automação do trabalho manual nas áreas de TI e Controladoria na conferência de faturas fiscais com múltiplos itens para alocação de centros de custo e chamados.
- **Destaques Técnicos:**
  - **Processamento 100% Client-Side:** Execução direta no navegador via JavaScript, garantindo custo zero de infraestrutura e sigilo absoluto sobre dados fiscais da empresa.
  - **Fragmentação Unitária de Produtos:** Decomposição automática de itens com quantidade múltipla em registros unitários, permitindo a correlação de diferentes chamados e centros de custo ao mesmo código de produto.
  - **Geração de Relatórios em PDF:** Criação instantânea de documento PDF formatado com dados da nota, detalhes dos itens e rateios preenchidos para validação contábil.
- **Stack:** `JavaScript`, `Tailwind CSS`, `PDF.js`, `jsPDF / AutoTable`.

[Repositório do NotaFácil](https://github.com/danmrtx/NotaFacil)

---

## Tecnologias e Habilidades

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
      <h4>Backend e Dados</h4>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <h4>IA e Automação</h4>
      <img src="https://img.shields.io/badge/Prompt_Engineering-8E75C4?style=flat-square&logo=openai&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/AI_Automation-FF6F00?style=flat-square&logo=google&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/LLM_Integration-412991?style=flat-square&logo=anthropic&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Process_Optimization-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <h4>Infraestrutura e Ferramentas</h4>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Suporte_Corporativo-4A154B?style=flat-square&logo=slack&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Redes_e_Hardware-232F3E?style=flat-square&logo=serverfault&logoColor=white" />
    </td>
  </tr>
</table>

---

## Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=danmrtx&show_icons=true&theme=tokyonight&locale=pt-br&hide_border=true&count_private=true" alt="Estatísticas no GitHub" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=danmrtx&layout=compact&theme=tokyonight&locale=pt-br&hide_border=true" alt="Linguagens mais utilizadas" height="150" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=danmrtx&theme=tokyonight&hide_border=true" alt="Streak no GitHub" />
</div>

---

<div align="center">
  <sub>Daniel Martins | Analista de TI e Desenvolvedor</sub>
</div>
