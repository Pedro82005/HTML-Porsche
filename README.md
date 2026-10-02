# HTML-Porsche

Readme · MD
Dashboard de Vendas Porsche
Dashboard interativa em HTML (arquivo único) que transforma uma base de 100 vendas da Porsche em respostas para perguntas de negócio. Projeto do desafio da DIO: sem limitações do Excel e publicado na web com GitHub Pages.

Link da dashboard publicada: cole aqui o link do GitHub Pages

Os dados deste exemplo são fictícios e foram criados só para demonstração. Para usar a planilha oficial do desafio, troque o conteúdo da constante DATA no index.html.

Perguntas de negócio
Quais modelos geram mais receita? Barras horizontais com a receita por modelo, em ordem decrescente.
Como a receita evolui por ano? Colunas com a receita total de cada ano.
Como os clientes pagam? Barra empilhada com a participação de cada método de pagamento.
O que a dashboard tem
Indicadores de topo: total de vendas, receita total e ticket médio.
Filtros por modelo, cidade, ano e método de pagamento. Tudo se atualiza junto.
Botão para limpar os filtros e mensagem clara quando nenhum resultado é encontrado.
Visual próprio: paleta vermelho, grafite e azul-petróleo, com as fontes Barlow Condensed e Barlow.
Layout responsivo, funciona no celular.
Tecnologias
HTML, CSS e JavaScript puros, sem bibliotecas. Só as fontes vêm do Google Fonts.

Como rodar localmente
Baixe o index.html e abra no navegador. Não precisa instalar nada.

Como publicar no GitHub Pages
Crie um repositório público na sua conta do GitHub.
Envie os arquivos index.html e README.md para a branch main.
Vá em Settings → Pages.
Em Build and deployment, escolha Deploy from a branch, selecione a branch main e a pasta / (root), e clique em Save.
Aguarde um ou dois minutos. O link aparece no topo da página de Pages, no formato https://seu-usuario.github.io/nome-do-repositorio/.
Estrutura
.
├── index.html   # dashboard completa (dados, estilo e lógica)
└── README.md
Como trocar os dados
Em index.html, cada venda é um objeto na constante DATA:

js
{"m":"Macan","c":"São Paulo","a":2024,"p":"Financiamento","v":545000}
m é o modelo, c a cidade, a o ano, p o método de pagamento e v o valor em reais. Os filtros e gráficos se ajustam aos valores que existirem.



