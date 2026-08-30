# Dashboard de Fechamento Comercial

Painel HTML estático de fechamento comercial, criado por **Milton Souza Macedo Junior**.

O arquivo único `index.html` apresenta o fechamento da equipe de vendas (Loja 02) no período de 24/06/2026 a 23/07/2026: KPIs de faturamento, evolução dos últimos seis meses, tendência dos 32 vendedores ativos, ranking de atendimentos e cards individuais por vendedor.

Não há backend, banco de dados nem etapa de build. Tudo roda no navegador.

## Como abrir

1. Clone o repositório:

```bash
git clone https://github.com/miltonjr-dev/Dashbord-fechamento.git
cd Dashbord-fechamento
```

2. Abra `index.html` no navegador (duplo clique no arquivo, ou arraste para uma aba).

Alternativa em terminal:

```bash
# macOS
open index.html

# Linux (exemplo)
xdg-open index.html
```

Não é necessário instalar dependências nem subir um servidor.

Na interface:

- **Gerencial** — faturamento, gráficos e ranking de atendimentos
- **Vendedores** — análise individual (alta, estável, queda)
- **Baixar PDF** — usa a impressão do navegador
- **Baixar Dashboard** — salva uma cópia do HTML
- **Baixar CSV** — exporta o ranking de atendimentos

## Stack

| Camada | Tecnologia |
| --- | --- |
| Marcação | HTML5 (`lang="pt-BR"`) |
| Estilo | CSS3 (grid, print, responsivo) |
| Lógica | JavaScript vanilla |
| Gráficos | [Chart.js](https://www.chartjs.org/) v4.4.1 (embutido no HTML) |

Arquivo principal: [`index.html`](index.html).

## Licença

Distribuído sob a licença [MIT](LICENSE). Copyright © 2026 Milton Souza Macedo Junior.
