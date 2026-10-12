# 📊 Relatório Financeiro com Foco na Experiência do Usuário

Projeto do desafio **"Atualizando Relatório Financeiro com Foco na Experiência do Usuário"** (DIO).
O objetivo foi pegar o primeiro relatório criativo desenvolvido no curso e reformulá-lo pensando em quem vai usá-lo: onde cada elemento fica na tela, o contraste entre eles, a proporção entre as áreas e a forma como os dados são segmentados e navegados.

> 🔗 **Relatório publicado no Power BI Service:** _(cole aqui o link, se publicou)_

---

## 🎯 Objetivo

Evoluir um relatório financeiro de vendas em Power BI aplicando princípios de UX:

| Princípio | Como foi aplicado |
|---|---|
| **Posicionamento** | Título e cartões de KPI no topo, filtros agrupados em uma área própria e gráficos principais no centro, seguindo a ordem natural de leitura. |
| **Contraste** | Fundo escuro/roxo com visuais e textos claros para destacar números e títulos. |
| **Proporção áurea** | Divisão da tela em uma área principal maior (gráficos) e uma área secundária menor (filtros/KPIs), aproximando a proporção ~1,618. |
| **Segmentação de dados** | Segmentador de datas, filtros por clique nos gráficos e botão para limpar filtros. |

> Como visto no curso, não são regras rígidas: a ideia é entendê-las e saber quando quebrá-las para dar personalidade ao relatório.

---

## 🧩 O que tem no relatório

**Páginas**
- **Home page** – página de entrada com botão de navegação para o relatório.
- **Principal** – painel de vendas com os visuais abaixo.

**Visuais**
- 5 cartões de KPI: Vendas (Sales), COGS, Unidades Vendidas (Units Sold) e Descontos (Discounts).
- Vendas por Segmento: gráfico de barras agrupadas ⇄ gráfico de rosca.
- Vendas por País: mapa ⇄ treemap.
- Vendas por Período: gráfico de área com hierarquia de datas (trimestre/mês), alternando entre **distribuição por semestre** e **por meses**.
- Vendas por Produto: gráfico de barras.
- Segmentador de data ("Selecione a data").

**Interatividade**
- Botões com imagem que alternam entre visuais usando **indicadores (bookmarks)**: `Gráfico Pie`, `Gráfico Barra`, `Gráfico Tremap`, `Gráfico Map`, `Distribuição por semestre`, `Distribuição por meses`.
- Botão **Clean data** para limpar filtros e voltar ao estado inicial.
- Botões de navegação (**Home** e **Next**) com destaque visual ao focalizar e ao selecionar.
- Visuais personalizados incluídos no arquivo: Chiclet Slicer, Bullet Chart, Power KPI e Sankey.

---

## 🗂️ Dados

Base de exemplo **financials** (Financial Sample), com colunas como `Segment`, `Country`, `Product`, `Sales`, `COGS`, `Units Sold`, `Discounts` e `Date`.

---

## 📁 Estrutura do repositório

```
.
├── README.md
├── powerbi/
│   ├── relatorio_inicial.pbix        # primeira versão (relatório criativo)
│   └── relatorio_atualizado.pbix     # versão final com foco em UX
├── docs/
│   └── desafio.docx                  # enunciado do desafio
└── images/
    ├── home.png
    └── principal.png                 # capturas de tela
```

---

## 🖼️ Prévia

_(adicione aqui as capturas de tela)_

![Home](images/home.png)
![Principal](images/principal.png)

---

## ▶️ Como abrir

1. Instale o [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Baixe `powerbi/relatorio_atualizado.pbix`.
3. Abra o arquivo e, se pedido, atualize a fonte de dados.
4. Use o modo de apresentação para testar os botões e indicadores.

---

## 🛠️ Tecnologias

Power BI Desktop · Power BI Service · Indicadores (Bookmarks) · Botões de ação · Visuais personalizados · Design de relatórios (Canva para imagens de fundo)

---

## 📚 Aprendizados

- Planejar o layout antes de inserir os visuais.
- Usar indicadores e botões para criar uma navegação parecida com a de um aplicativo.
- Equilibrar estética e legibilidade: contraste, alinhamento e espaço em branco.
- Reduzir a poluição visual alternando visuais em vez de empilhá-los.

---

## 👤 Autor

**Seu Nome** · [LinkedIn](#) · [GitHub](#)

Projeto desenvolvido como parte da formação **Power BI Analyst – DIO + Santander Open Academy**.
