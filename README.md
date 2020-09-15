# Descri��o do trabalho

Crie uma classe chamada Produto que deve possuir um nome, um c�digo e um pre�o. Sobrescreva os m�todos equals() e hashCode() de Object (veja se��o sobre esses m�todos), de forma a serem considerados iguais instancias de Produto que possuam o mesmo c�digo.

Crie uma classe chamada ProdutoComTamanho que estenda a classe Produto. Essa classe deve possuir uma informa��o adicional de tamanho. Um exemplo seria o tamanho de uma roupa ou a numera��o de um cal�ado. M�todo equals() e hashCode() devem ser sobrescritos de forma que um produto com mesmo c�digo e tamanhos diferentes s�o considerados diferentes.

Crie uma classe CarrinhoDeCompras que armazene em um atributo interno do tipo HashMap cada produto adicionado no carrinho e sua respectiva quantidade. O m�todo adicionaProduto() deve receber a instancia do produto e a quantidade. Caso o produto j� exista no HashMap, a quantidade deve ser somada a que j� existe no carrinho. Deve haver tamb�m um m�todo removeProduto() que tamb�m recebe a instancia do produto e a quantidade a ser removida. Observe que produtos de tamanhos diferentes devem ser considerados como produtos diferentes no carrinho. O carrinho deve possuir um m�todo que calcula o valor total da compra.

Crie testes com Unit para a classe Produto, para a classe ProdutoComTamanho e para a classe CarrinhoDeCompras. Os testes de cada classe devem ser colocados em classes separadas e devem estar em um diret�rio de c�digo diferente das classes de produ��o.


