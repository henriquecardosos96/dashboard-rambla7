# 📊 Rambla7 · Dashboard de Marketing

> Dashboard interativo de performance para a **Agência Rambla7 Agromarketing** — desenvolvido para apresentação e prospecção de clientes via LinkedIn e GitHub Pages.

![Rambla7 Agromarketing](https://img.shields.io/badge/Rambla7-Agromarketing-C8620A?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-Standalone-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-4.4.1-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Responsivo](https://img.shields.io/badge/Mobile-Responsivo-2D7A3A?style=for-the-badge&logo=responsive&logoColor=white)

---

## 🌾 Sobre o Projeto

Este dashboard foi criado como **protótipo comercial** da Agência Rambla7 para demonstrar aos seus clientes do agronegócio como seria uma plataforma de acompanhamento de campanhas de marketing digital.

O arquivo é **100% standalone** — um único `.html` sem dependências externas além de CDN público — o que facilita o compartilhamento direto via link do GitHub Pages ou LinkedIn.

---

## ✨ Funcionalidades

### 📈 KPIs em Tempo Real
| Indicador | Descrição |
|---|---|
| 💰 Investimento Total | Verba total alocada em mídia |
| 🌱 Faturamento Gerado | Receita atribuída às campanhas |
| 📊 ROAS Médio | Retorno sobre o investimento (×) |
| 👁️ Impressões Totais | Total de exibições dos anúncios |
| 🛒 Vendas Totais | Conversões registradas |

### 📊 Gráficos Interativos
- **Faturamento por Cliente** — Top 10, barras horizontais com destaque por posição
- **ROAS por Cliente** — Ranking de retorno sobre investimento
- **Desempenho por Campanha** — Campanhas A, B, C e D comparadas
- **Performance por Anúncio** — Faturamento por criativo (Anúncio 1 a 5)
- **Impressões, Alcance e Page Views** — Donuts por cliente (Top 8)

### 🔍 Filtros Interativos
- **Filtro por Cliente** — 27 clientes do portfólio Rambla7
- **Filtro por Campanha** — Campanhas A, B, C e D
- Os KPIs e gráficos atualizam instantaneamente ao filtrar

### 🏆 Ranking de Clientes
Tabela completa com todas as métricas consolidadas por cliente, ordenada por faturamento, com medalhas (🥇🥈🥉) e barra visual de ROAS.

---

## 📱 Responsividade

O dashboard é totalmente adaptado para todos os dispositivos:

| Dispositivo | Comportamento |
|---|---|
| 🖥️ Desktop (> 1024px) | Sidebar fixa lateral, grids completos, todos os filtros visíveis |
| 📱 Tablet (768–1024px) | Sidebar reduzida, gráficos em 2 colunas |
| 📲 Mobile (< 768px) | Bottom navigation, sidebar deslizante com overlay, filtros em barra própria, KPIs em 2 colunas |
| 📲 Small Phone (< 400px) | Layout ultra-compacto otimizado para telas de 360px |

---

## 🚀 Como Publicar no GitHub Pages

### 1. Crie o repositório
```bash
# Crie um repositório público no GitHub com o nome desejado
# Ex: rambla7-dashboard
```

### 2. Faça o upload do arquivo
```bash
git init
git add rambla7_dashboard.html
git commit -m "feat: add Rambla7 marketing dashboard"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/rambla7-dashboard.git
git push -u origin main
```

### 3. Ative o GitHub Pages
1. Acesse **Settings** → **Pages** no repositório
2. Em **Source**, selecione `Deploy from a branch`
3. Escolha a branch `main` e pasta `/ (root)`
4. Clique em **Save**

### 4. Acesse o link gerado
```
https://SEU_USUARIO.github.io/rambla7-dashboard/rambla7_dashboard.html
```

> ⏱️ O GitHub Pages pode levar até 2 minutos para ficar disponível após a primeira publicação.

---

## 🏢 Clientes no Dashboard

O dashboard contempla **27 marcas** do portfólio da Rambla7:

| | | | |
|---|---|---|---|
| Agro Rural | Ballagro | BioSyn | Bom Jesus |
| C.Vale | Cibio | CLAC | Coagro |
| Coopavel | CooperOeste | Copagril | Copérdia |
| Eurotec Group | Eurotec Nutrition | Fertilis | Frísia |
| Granja Brasília | Heel Vet | Kraemer | Máxima Agronegócios |
| Nutrali | Palmali | Prado Multiespécies | Prado Saúde Animal |
| Soma Energia | Tacto Nutrição | Topnutri | |

---

## 🗂️ Estrutura do Projeto

```
rambla7-dashboard/
│
├── rambla7_dashboard.html   # Dashboard principal (arquivo único)
├── base_marketing_agro.csv  # Base de dados original (1.000 registros)
└── README.md                # Este arquivo
```

> **Nota:** A logo da Rambla7 está embutida diretamente no HTML em formato Base64 — nenhum arquivo de imagem externo é necessário.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|---|---|---|
| HTML5 | — | Estrutura do dashboard |
| CSS3 | — | Layout responsivo, variáveis, media queries |
| JavaScript (Vanilla) | ES2020+ | Lógica de filtros, renderização dinâmica |
| [Chart.js](https://www.chartjs.org/) | 4.4.1 | Gráficos interativos (bar, doughnut) |
| [Google Fonts — Inter](https://fonts.google.com/specimen/Inter) | — | Tipografia |

---

## 📐 Paleta de Cores

```css
--orange:      #C8620A   /* Cor principal Rambla7 */
--green:       #2D7A3A   /* Agronegócio */
--yellow:      #F5C800   /* Destaque / Logo */
--bg:          #F4F5F8   /* Fundo da página */
--surface:     #FFFFFF   /* Cards e superfícies */
--text-primary:#16191F   /* Texto principal */
```

---

## 📊 Métricas da Base de Dados

| Métrica | Total |
|---|---|
| Registros | 1.000 linhas |
| Clientes | 27 marcas |
| Campanhas | 4 (A, B, C, D) |
| Criativos | 5 anúncios |
| Investimento total | R$ 5,28M |
| Faturamento total | R$ 1,44B |
| ROAS médio | 273× |
| Impressões totais | 250,3M |
| Vendas totais | 5,28M |

---

## 📬 Contato

**Agência Rambla7 · Agromarketing**

- 🌐 [rambla7.com.br](https://rambla7.com.br)
- 📧 contato@rambla7.com.br
- 📞 41 99287-8063
- 💼 [LinkedIn](https://www.linkedin.com/company/agenciarambla7)

---

> *Dashboard desenvolvido como protótipo comercial para demonstração de capacidade analítica e tecnológica da Agência Rambla7 no segmento de agromarketing.*
