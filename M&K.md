Crie uma aplicação web responsiva em HTML, CSS e JavaScript que funcione como um dashboard financeiro no estilo "Barbiecore" (com tema rosa e design estético/fofo).

**Estrutura da página:**

1. **Cabeçalho:**
   - Título estilizado: "Planilha Financeira" com estética fofa/rosa.
   - Cards de resumo no topo mostrando "Média de Gastos Variáveis" e "Balanço Fixos + Variáveis" com valores destacados em R$.

2. **Gráficos (usando a biblioteca Chart.js):**
   - Lado a lado: Dois gráficos no formato Donut (Rosca).
   - O primeiro mostrando a distribuição percentual das categorias.
   - O segundo mostrando a distribuição por categorias específicas com legenda ao centro (Casa, Educação, Farmácia, Fast food, Mercado, Trabalho, Transporte, Vestuário).
   - Paleta de cores dos gráficos em tons de rosa, lilás e pastel.

3. **Tabela de Gastos Variáveis:**
   - Colunas: Nome, Forma de Pagamento (Dropdown: Pix, Débito, Crédito), Categoria (Dropdown estilizado com tags coloridas), Valor (R$) e Status (Checkbox "Pago?").
   - Adicione linhas interativas para entrada de dados.
   - Linha final com o cálculo automático do TOTAL em R$.

4. **Tabela de Assinaturas/Fixos:**
   - Tabela menor para assinaturas (Ex: Netflix, Spotify, Nuvem).
   - Colunas: Descrição, Valor e Checkbox "Pago?".
   - Totalizador automático no rodapé da tabela.

5. **Estilização (CSS):**
   - Utilize uma paleta de cores rosa pastel, magenta e branco (#ffe6f0, #ff66b2, #ffffff, #d87093).
   - Fontes arredondadas e modernas (ex: 'Poppins' ou 'Nunito').
   - Bordas arredondadas (border-radius), sombras suaves e layout limpo.
   - Adicione suporte a cálculo automático dos totais dinamicamente via JS ao alterar qualquer valor.