# Prática Bootstrap

## Atividade 01

Nesta atividade, você irá criar um layout de página web responsivo utilizando os principais recursos do Bootstrap 5: containers, margens, paddings, sistema de grid e Flexbox. O objetivo é solidificar seu entendimento sobre como combinar essas ferramentas para estruturar o conteúdo de forma eficaz e adaptável a diferentes dispositivos.


Imagine que você precisa criar a estrutura básica de uma página inicial para um blog sobre tecnologia. Essa página deve conter um cabeçalho, uma seção principal com artigos em destaque e uma barra lateral com informações adicionais, além de um rodapé. O layout deve se ajustar bem em telas grandes (desktop), tablets e smartphones.




    Crie um arquivo HTML chamado index.html.
    Adicione a estrutura básica de um documento HTML5 ( <!DOCTYPE html>, <html>, <head>, <body>).
    Inclua a folha de estilos do Bootstrap 5. Você pode fazer isso adicionando a seguinte linha dentro da tag <head>:


    Dentro da tag <body>, crie um elemento <header> e um elemento <main>.
    Dentro de cada um desses elementos, utilize um container do Bootstrap para centralizar o conteúdo e definir uma largura máxima responsiva. Escolha entre .container (largura fixa em diferentes breakpoints) ou .container-fluid (largura total). Para esta atividade, use .container.


    Dentro do <header>, crie elementos para o título do blog e uma possível navegação (mesmo que vazia).
    Utilize as classes de Flexbox do Bootstrap (d-flex, justify-content-between, align-items-center) para alinhar o título à esquerda e a navegação à direita.
    Adicione classes de padding (py-3) para espaçamento vertical dentro do cabeçalho.


    Dentro da <main> e da div com a classe row, utilize o sistema de grid do Bootstrap para dividir o espaço em colunas.
    Para telas grandes (acima de 992px), a seção principal deve ocupar 8 colunas (col-lg-8) e a barra lateral 4 colunas (col-lg-4).
    Para telas menores (abaixo de 992px), ambas devem ocupar a largura total (col-12), com a barra lateral aparecendo abaixo da seção principal.
    Dentro da seção principal, crie alguns elementos representando artigos em destaque.
    Dentro da barra lateral, adicione algum conteúdo simulado (ex: links para categorias, informações sobre o autor).
    Utilize classes de margin (mb-4 na seção principal para espaçamento abaixo dos artigos) e padding (p-3 na barra lateral para espaçamento interno).


    Dentro do <footer>, adicione informações de direitos autorais ou outros links.
    Utilize as classes de Flexbox (d-flex, justify-content-center, align-items-center) para centralizar o conteúdo do rodapé.
    Adicione classes de padding (py-3) e uma cor de fundo (bg-light).


    Salve o arquivo index.html e abra-o em seu navegador.
    Redimensione a janela do navegador para observar como o layout se adapta a diferentes tamanhos de tela, demonstrando a responsividade do Bootstrap.




    Tente substituir .container por .container-fluid e veja a diferença.
    Utilize classes como mt-, mb-, ms-, me-, pt-, pb-, ps-, pe- com diferentes valores (0 a 5 e auto) para ajustar o espaçamento entre os elementos.
    Use as classes de grid responsivas (col-md-, col-sm-, col-xs- - lembrando que col- sem sufixo se aplica a todos os tamanhos) para criar layouts mais complexos em diferentes dispositivos.
    Experimente justify-content-start, justify-content-around, align-items-start, align-items-end, align-self-start, etc.
    Enriqueça o conteúdo da seção principal e da barra lateral para visualizar melhor o layout com mais informações.
    Se desejar, adicione suas próprias regras de CSS para personalizar ainda mais a aparência dos elementos.

Ao completar esta atividade, você terá praticado a combinação dos principais recursos de layout do Bootstrap 5, construindo uma estrutura de página responsiva e organizada. Este é um passo fundamental para criar interfaces web modernas e adaptáveis.

## Atividade 02

Instruções Gerais para os Alunos: Para cada questão, crie um arquivo HTML com a estrutura básica necessária e um arquivo CSS vinculado para aplicar os estilos. Concentre-se em usar as propriedades de layout mencionadas para alcançar o resultado visual descrito. Considere a responsividade, mesmo que não explicitamente solicitada em todas as questões.
Questões Práticas:

Cartão de Perfil Simples:

    Tarefa: Crie um componente "cartão de perfil" que contenha uma imagem (avatar), um nome de usuário e uma breve biografia.
    Requisitos de Layout:
    O cartão deve ter uma largura fixa de 300px e uma borda sutil.
    A imagem deve ficar à esquerda, o nome de usuário e a biografia à direita.
    Deve haver um padding interno de 15px no cartão.
    Use margin para criar um espaçamento de 10px entre a imagem e o bloco de texto (nome/biografia).
    Tecnologia principal: Flexbox para o layout interno do cartão; Margin/Padding para espaçamentos.







Galeria de Imagens Responsiva com Flexbox:

    Tarefa: Crie uma galeria de imagens onde as imagens se ajustam automaticamente ao tamanho da tela.
    Requisitos de Layout:
    Use um container flexível para as imagens.
    As imagens devem ter uma largura base (ex: 150px), mas devem poder crescer ou encolher para preencher o espaço disponível.
    Quando não houver espaço suficiente na linha, as imagens devem quebrar para a próxima linha (flex-wrap).
    Adicione um gap (gutter) de 10px entre as imagens.
    Tecnologia principal: Flexbox (flex-grow, flex-shrink, flex-basis, flex-wrap, gap).







Barra de Navegação Horizontal:

    Tarefa: Construa uma barra de navegação horizontal.
    Requisitos de Layout:
    Os links de navegação devem ser exibidos em linha.
    O logo deve ficar à esquerda e os links de navegação à direita.
    Os links devem estar espaçados uniformemente ou com espaço entre eles.
    A barra deve ter um padding vertical.
    Tecnologia principal: Flexbox (justify-content, align-items).







Layout de Página com Grid (Holy Grail Simplificado):

    Tarefa: Crie uma estrutura de página básica com cabeçalho, conteúdo principal, barra lateral e rodapé.
    Requisitos de Layout:
    O cabeçalho e o rodapé devem ocupar toda a largura.
    O conteúdo principal deve ocupar o espaço maior e a barra lateral um espaço menor ao lado.
    Defina áreas da grade usando grid-template-areas.
    Adicione gap para espaçamento entre as seções.
    Tecnologia principal: CSS Grid (grid-template-columns, grid-template-rows, grid-template-areas, gap).







Centralização Perfeita com Flexbox:

    Tarefa: Centralize um div (com dimensões fixas, ex: 100px por 100px) tanto horizontalmente quanto verticalmente dentro de seu container pai.
    Requisitos de Layout:
    O container pai deve ocupar toda a altura e largura da viewport.
    Tecnologia principal: Flexbox (align-items, justify-content no container pai).







Centralização Perfeita com Grid:

    Tarefa: Repita o desafio da questão 5, mas desta vez utilizando CSS Grid para centralizar o div.
    Requisitos de Layout:
    O container pai deve ocupar toda a altura e largura da viewport.
    Tecnologia principal: CSS Grid (place-items: center ou align-items/justify-items no container pai).







Formulário com Labels e Inputs Alinhados:

    Tarefa: Crie um formulário onde os labels e os inputs estejam bem alinhados.
    Requisitos de Layout:
    Cada par de label/input deve estar em sua própria linha.
    Os labels devem estar alinhados à direita e os inputs à esquerda, ou os labels acima dos inputs.
    Pesquise e aplique uma técnica usando Flexbox ou Grid para alinhar os campos de forma consistente.
    Adicione margin abaixo de cada par label/input para espaçamento.
    Tecnologia principal: Flexbox ou Grid, Margin.







Layout de Blog com Colunas de Texto:

    Tarefa: Crie um layout de artigo de blog onde o texto principal é dividido em múltiplas colunas.
    Requisitos de Layout:
    Use a propriedade columns do CSS para dividir um bloco de texto longo em 2 ou 3 colunas.
    Adicione um column-gap para o gutter entre as colunas.
    Opcional: Adicione uma column-rule (linha vertical entre as colunas).
    Tecnologia principal: CSS Columns (columns, column-count, column-gap, column-rule).







Container Centralizado com Largura Máxima:

    Tarefa: Crie um container que centralize o conteúdo da página e tenha uma largura máxima, mas seja fluido abaixo dessa largura.
    Requisitos de Layout:
    O container deve ter uma max-width (ex: 960px).
    O container deve ser centralizado horizontalmente na página.
    Use margin: auto para a centralização horizontal.
    Adicione padding interno ao container.
    Tecnologia principal: Margin, Padding, max-width.







Grid de Cards com Número Fixo de Colunas:

    Tarefa: Crie um grid de cards (componentes como o da questão 1) que sempre exiba 3 colunas, independentemente da largura da tela (os cards vão encolher).
    Requisitos de Layout:
    Use CSS Grid com grid-template-columns para definir 3 colunas de tamanhos iguais (ex: 1fr 1fr 1fr).
    Adicione um gap entre os cards.
    Tecnologia principal: CSS Grid (grid-template-columns, gap).







Grid de Cards Responsivo (Auto-Fit/Auto-Fill):

    Tarefa: Crie um grid de cards que seja responsivo, ajustando o número de colunas com base na largura disponível.
    Requisitos de Layout:
    Use CSS Grid com grid-template-columns e as palavras-chave auto-fit ou auto-fill em conjunto com minmax().
    Defina um tamanho mínimo e máximo para os cards.
    Adicione um gap entre os cards.
    Tecnologia principal: CSS Grid (grid-template-columns, auto-fit / auto-fill, minmax(), gap). Pesquise a diferença entre auto-fit e auto-fill.







Componente de Preços com Alinhamento Flex:

    Tarefa: Crie um componente de "plano de preços" com um título, lista de recursos e um botão de "Comprar".
    Requisitos de Layout:
    Use Flexbox para organizar os elementos internos.
    O título deve estar no topo, a lista de recursos no meio e o botão sempre na parte inferior do card, mesmo que a lista de recursos tenha tamanhos diferentes em cards adjacentes.
    Pesquise como usar margin-top: auto em um item flex para empurrá-lo para o final do container flexível.
    Tecnologia principal: Flexbox (flex-direction: column, margin-top: auto).







Layout de Rodapé com Colunas:

    Tarefa: Crie um rodapé de site com múltiplas colunas (ex: "Sobre Nós", "Links Úteis", "Contato").
    Requisitos de Layout:
    Use Flexbox ou Grid para criar as colunas.
    As colunas devem se distribuir igualmente no espaço disponível.
    Adicione padding ao rodapé e gap ou margin entre as colunas.
    Tecnologia principal: Flexbox ou Grid, Padding, Gap/Margin.







Box Model e box-sizing:

    Tarefa: Crie dois divs lado a lado. Ambos devem ter width: 150px, padding: 20px e border: 5px solid black.
    Requisitos de Layout:
    No primeiro div, use o box-sizing padrão (content-box).
    No segundo div, aplique box-sizing: border-box.
    Observe e explique a diferença no tamanho total renderizado dos dois divs. Use Flexbox para colocá-los lado a lado e observe o impacto no layout.
    Tecnologia principal: box-sizing, Padding, Border, Width, Flexbox (para visualização lado a lado).







Sobreposição de Elementos com Grid:

    Tarefa: Crie um layout onde uma imagem de fundo ocupe uma célula da grade e um texto com fundo semi-transparente se sobreponha a uma parte dessa imagem.
    Requisitos de Layout:
    Defina uma grade simples (ex: 2x2).
    Posicione a imagem para ocupar, por exemplo, grid-column: 1 / 3 e grid-row: 1 / 2.
    Posicione o bloco de texto para ocupar, por exemplo, grid-column: 2 / 3 e grid-row: 1 / 2, e ajuste seu alinhamento (align-self, justify-self) para criar a sobreposição desejada.
    Use z-index se necessário, embora o Grid geralmente lide bem com a ordem de pintura baseada na ordem do DOM ou posicionamento explícito.
    Tecnologia principal: CSS Grid (posicionamento de itens), z-index (potencialmente).







Controle de Ordem Visual com Flexbox:

    Tarefa: Dado um HTML com três blocos (div), A, B e C, nesta ordem.
    Requisitos de Layout:
    Usando Flexbox, exiba-os visualmente na ordem B, C, A em telas maiores.
    Em telas menores (usando uma media query), reverta para a ordem A, B, C.
    Pesquise e utilize a propriedade order.
    Tecnologia principal: Flexbox (order), Media Queries.







Espaçamento Interno vs. Externo em um "Botão":

    Tarefa: Crie um elemento que se pareça com um botão (ex: um link estilizado).
    Requisitos de Layout:
    Adicione padding para criar espaço entre o texto do botão e suas bordas.
    Adicione margin para criar espaço entre este botão e outros elementos adjacentes.
    Experimente diferentes valores e observe como cada propriedade afeta o "espaço respirável" do botão e seu posicionamento relativo a outros.
    Tecnologia principal: Padding, Margin, Border.







Layout Assimétrico com Grid Areas:

    Tarefa: Crie um layout de página mais complexo e assimétrico usando grid-template-areas. Por exemplo, um banner largo no topo, abaixo dele uma coluna fina à esquerda, uma área de conteúdo principal grande e uma coluna um pouco mais larga à direita.
    Requisitos de Layout:
    Defina nomes para as áreas (ex: "header", "sidebar-left", "main", "sidebar-right", "footer").
    Use grid-template-areas para mapear essas áreas para a grade.
    Adicione gap entre as áreas.
    Tecnologia principal: CSS Grid (grid-template-areas, grid-template-columns, grid-template-rows, gap).







Gutters Consistentes em Flexbox e Grid:

    Tarefa: Crie dois layouts de galeria simples: um usando Flexbox e outro usando Grid.
    Requisitos de Layout:
    Ambos devem ter 3 itens por linha.
    O desafio é implementar um gutter (espaçamento) de 16px entre os itens em AMBAS as galerias usando a propriedade gap (e suas variantes row-gap, column-gap se necessário).
    Pesquise a compatibilidade da propriedade gap em Flexbox e Grid.
    Tecnologia principal: Flexbox (gap), CSS Grid (gap).







Desafio Combinado: Painel de Dashboard:

    Tarefa: Crie um pequeno painel de "dashboard" com vários widgets.
    Requisitos de Layout:
    Use um container Grid para o layout geral do painel (ex: 2 colunas, várias linhas).
    Cada widget (que pode ser um div simples com um título e algum conteúdo) deve ser um item da grade.
    Dentro de cada widget, use Flexbox para alinhar seu conteúdo interno (ex: título no topo, conteúdo abaixo, talvez um ícone ao lado do título).
    Use padding dentro dos widgets e gap no container Grid para espaçamentos.
    Tecnologia principal: CSS Grid (layout principal), Flexbox (layout interno dos widgets), Padding, Gap.

