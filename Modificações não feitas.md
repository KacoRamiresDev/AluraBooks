Tenho aqui algumas coisas que não consegui fazer para deixar o projeto mais proximo do Figma. Algumas delas são:

Pagination: Quis deixar sempre 4 bullets independente do número de livro que tivesse para manter o padrão do figma mas não encontrei a propriedade que faz isso.

Navigation: não soube deixar igual ao do Figma, usei uma "gambiarra" pra deixar imagens no lugar do navigation original criado por código, mas optei por não deixar a "gambiarra", mas sim o original pra não correr o risco das imagens sumirem (o improviso que coloca as imagens no lugar do original está “comentado” no CSS através da tag /* ... */ na linha 141-150 no final do código da arquivo ./css/carrossel).

O tamanho e o padding dos botões também não ficaram idênticos aos do figma
Além dos botões continuarem em cima da imagem dos livros e não ligeiramente ao lado deles, por padrão os botões ficam levemente transparentes quando inativos, decidi deixar assim por achar mais bonito.

Lista tópicos: Fiz algumas pesquisas, mas não achei como trocar a ordem dos itens da lista a minha vontade então usei um Position: relative; no elemento pai e uma Order: -5; no elemento filho que eu queria voltar na lista, o filho agora se encontra no começo da lista, mas deveria esta como segundo item (por isso o Order: -5;) de acordo com o figma.
Também quis deixar os botões do “tópicos visitados recentemente” de um jeito que ficasse sempre quatro por linha, por estética mesmo. Mas não sei ainda como se faz isso.

Inputs: Não gostei muito do resultado das Background-images dos inputs pois se a resolução da tela estiver muito longe da definida no Media Query a Background-image se afasta muito do texto do placeholder. Queria saber um modo de deixar a Image sempre na mesma distância do texto.

Classes: Com relação as Classes eu fiquei em dúvida e usei no começo apenas palavras em inglês (search, header...), mas ainda não sou fluente então decidi deixar em português no começo. Comecei deixando todas as classes no singular (item, contato, linha...), mas por questão de facilidade para reconhecer a classe no HTML resolvi nos próximos projetos ser mais literal, logo se a Section só possui um tópico, por exemplo, sua classe se chamará “topico”, já se possuir dois ou mais uso o plural “topicos”, mas como esse projeto me servirá de estudo mais tarde as classes que estão em inglês permaneceram assim para que eu não esqueça de começar a usa-las assim.
