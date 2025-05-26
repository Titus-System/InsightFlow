# InsightFlow
📦 Plataforma de Comércio Exterior do Brasil  

![logo](docs/logo_if_semfundo.png)

## 📖 Sobre o Projeto  
Este projeto visa concentrar dados de comércio exterior no Brasil, fornecendo informações essenciais para profissionais de logística e tomadores de decisão.  
A plataforma oferecerá análises interativas, busca avançada e previsão de tendências para facilitar a compreensão do mercado.  

## 🎯 Objetivos Principais  
✅ Centralizar informações de importação e exportação do Brasil.  
✅ Apresentar gráficos interativos para identificação rápida de padrões.  
✅ Disponibilizar um painel detalhado com dados de cada estado.  
✅ Permitir busca e filtragem por código NCM e categorias personalizadas.  
✅ Comparar o desempenho comercial dos estados.  
✅ Identificar tendências e oportunidades de mercado com inteligência de dados.  

![VPC](docs/vpc.png)

## 🚀 Funcionalidades do Site
- **Painel com Gráficos Interativos**: Visualização de exportações e importações por estado.  
- **Detalhamento por Estado**: Ranking de produtos, evolução histórica e balança comercial.  
- **Busca Avançada**: Filtros personalizados e pesquisa por código NCM.  
- **Comparação Comercial**: Rankeamento de exportação e importação por Valor FOB e Valor Agregado segundo critérios de NCM, SH4, países, e estados
- **Agregados por setores econômicos**: Agonegócio, Indústria, Bens de Consumo, Mineração, Setor Florestal, Tecnologia
- **Previsão de Tendências**: Uso de inteligência de dados para projeções futuras.
  - Modelo estatístico: **SARIMA**
- **Análises estatísticas**:
   - Regressão Linear
   - Volatilidade
   - Taxa de Crescimento Mensal
   - Sazonalidade
   - Concentração por país, estado e NCM

**Análises de tendências:**  
*Optamos por usar o modelo SARIMA (Seasonal ARIMA) porque estamos lidando com dados de séries temporais mensais que apresentam tendência e sazonalidade anual, como é comum em análises econômicas, de exportação/importação ou demanda. O modelo é bem estabelecido na estatística e econometria, sendo robusto para dados regulares e com padrão temporal.
Além disso, realizamos uma interpolação linear para tratar valores ausentes, garantindo continuidade nos dados, e ajustamos o modelo para gerar previsões com 24 meses de antecedência.
Escolhemos esse modelo pela sua interpretabilidade, confiabilidade e boa performance em séries temporais estruturadas.*

## 🛠️ Tecnologias Utilizadas
*Backend*
<p align="center">
  <img alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img alt="Flask" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg">
  <img alt="Pandas" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg" />
  <img alt="StatsModels" height="30" width="40"src="https://www.statsmodels.org/stable/_images/statsmodels-logo-v2.svg">
  <img alt="PostgreSQL" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg">
</p>

*Frontend*
<p align="center">
  <img alt="Typescript" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
  <img alt="React" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original-wordmark.svg" />
  <img alt="Vite" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitejs/vitejs-original.svg" />
  <img alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img alt="Tailwind" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg">
</p>

*Auxiliares*
<p align="center">
  <img alt="Git" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg">
  <img alt="Git" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg">
  <img alt="Figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg">
  <img alt="Jira" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg">
</p>

## ⚡ Desenvolvimento Ágil
O projeto foi feito seguindo o método Ágil SCRUM, dividindo o trabalho em sprints de 21 dias, com reuniões diáras, revisões e retrospectivas ao final. Essa abordagem permitiu uma gestão eficiente do projeto, com foco na entrega contínua de valor ao cliente. Ao longo das sprints, a equipe adquiriu e aprimorou habilidades técnicas e interpessoais, promovendo a resolução ágil de desafios e a adaptação a novas demandas.

## 📋 Backlog do Produto
![Backlog do Produto](docs/backlog_produto.PNG)

## 🎨 Protótipo (Figma)  
https://www.figma.com/design/yA0OeKu4rlyvuD8anzKlYH/insightFlow?node-id=0-1&t=Ae5HxVAYWcSI4RzY-1


## 📅 Cronograma
| Sprint            | Prazo      | Status    |
| ----------------- | ---------- | --------- |
| Kick Off          | 28/02/2025 | Concluído |
| Sprint 1          | 31/03/2025 | Concluído |
| Sprint 2          | 28/04/2025 |  Pendente |
| Sprint 3          | 05/05/2025 |  Pendente |
| Feira de Soluções | 29/05/2025 | Pendente  |

## 🥇 Equipe

|      Membro      |    Função     |                            Github                            |
| :--------------: | :-----------: | :----------------------------------------------------------: |
| Agatha Wei | Product Owner | <a href="https://github.com/Agathawei070"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Julia Santiago | Scrum Master | <a href="https://github.com/juliasantiaggo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Eduardo Ribeiro | Dev Team | <a href="https://github.com/eduardo-Rib"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Guilherme Henrique | Dev Team | <a href="https://github.com/Guih0412"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Julia Soares | Dev Team | <a href="https://github.com/juliasoares17"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Karina Ribeiro | Dev Team | <a href="https://github.com/karinaribeiro2"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Pedro Garcia | Dev Team  | <a href="https://github.com/pedro-fs-garcia"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
