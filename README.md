#Aprendendo sobre tabelas

A tag `table` permite organizar dados em linhas e colunas.

1. Estrutura básica: 
	A tag `table` é usada como o elemento pai para criar uma tabela HTML. As linhas da tabela são representadas pela tag `tr` (table row), e as células de dados são representadas pelas tags `td` (table data). Por outro lado, as células de cabeçalho são representadas pela tag `th` (table header).

2. Cabeçalho da tabela:
	Para criar um cabeçalho para a tabela, usar a tag `thead` e dentro dela, criar uma ou mais linhas de cabeçalho com a tag `tr`. As células de cabeçalho são definidas com a tag `th`.

3. Corpo da tabela:
	O corpo da tabela contém os dados propriamente ditos. Use a tag `tbody` para criar o corpo da tabela e, dentro dela, adicione as linhas de dados usando a tag `tr`. Cada célula de dados é representada pela tag `td`, que contém o conteúdo da célula.

4. Rodapé da tabela:
	O `tfoot` é usado para agrupar as linhas de rodapé da tabela, e normalmente contém informações resumidas, totais ou notas explicativas sobre os dados apresentados na tabela.

5. Atributos e propriedades:
	* `border`: Define a espessura da borda da tabela.
	* `cellspacing`: Define o espaço entre as células da 		tabela.
	* `cellpadding`: Define o espaço entre o conteúdo da 		célula e a borda da célula.
	* `summary`: é usado para fornecer uma breve descrição 		ou resumo da tabela, descrevendo o conteúdo ou 		a finalidade da tabela de forma concisa.
  * `rowspan`: é usada para mesclar uma célula verticalmente em várias linhas. Você define o valor de `rowspan` para indicar quantas linhas a célula deve abranger.
  * `colspan`: é usada para mesclar uma célula horizontalmente em várias colunas. Você define o valor de `colspan` para indicar quantas colunas a célula deve abranger.

6. A tag `caption` deve ser usada como o primeiro elemento filho dentro da tag `table` e normalmente fica acima da tabela, fornecendo uma descrição ou título conciso para a tabela.

7. Tabelas aninhadas:
	É possível aninhar tabelas dentro de outras tabelas, criando assim estruturas mais complexas.