# Documentacao_MDS

Instruções breves para conversão de arquivos .word para .rst
master

Irei incluir o link para a documentação da linguagem RST, é uma linguagem bem simples que auxilia muito na construção dos arquivos.
Observem os arquivos ja feitos e tentem tirar algo deles que queiram replicar.
Muita coisa que iremos fazer sera muito Teste e Erro, logo ainda há o que ser acrescentado neste documento.

Testes
1 - Installe o Pandoc, o instalador esta na pasta "pandoc".

2 - Coloque o arquivo Word desejado na pasta "_docx"

2.1 - Para um conversão eficiente do arquivo deve ser executado algumas ações no proposito de se ter menos trabalho na
edição do arquivo .rst

Entre elas estão:

A) Verificar se titulos estão com o estilo do Word "Titulo 1", "Titulo 2" etc etc, não importa o tamanho que ele sera
ou sua fonte, mas sim se ele esta como essa categoria.
(Vi que em varios documentos elas estão como "topicos" e não Titulos, verifiquem isto)

B) Excluir o Sumario que há no inicio do Documento, há uma função a ser escrita nos arquivos .rst que já cria um sumario
automatico com todos os topicos(Por isto a importancia do "Titulo 1", "Titulo 2"...)

MAIS INFORMAÇÕES VIRAO AQUI

3 - Após ter editado o arquivo Word iremos converter-lo atraves do script "ConversorRST". Para isto, salve o documento editado ou renomeie-o para algo mais simples e pratico.

3.1 - Siga os passos do script e seu documento .rst sera gerado e estara na pasta "_topicos" com o nome de saida que voce mencionou.

4 - Abra o arquivo e use o preview para ver como a pagina iria ficar no ReadTheDocs, irão ter erros, alguns mais simples e outros mais chatos.

1 - Installe o Pandoc, o instalador esta na pasta.

2 - Coloque o arquivo Word desejado na pasta "_docx"
	
	2.1 - Para um conversão eficiente do arquivo deve ser executado algumas ações no proposito de se ter menos trabalho na
	edição do arquivo .rst

	Entre elas estão:
		A) Verificar se titulos estão com o estilo do Word "Titulo 1", "Titulo 2" etc etc, não importa o tamanho que ele sera
		ou sua fonte, mas sim se ele esta como essa categoria.
		(Vi que em varios documentos elas estão como "topicos" e não Titulos, verifiquem isto)

		B) Excluir o Sumario que há no inicio do Documento, há uma função a ser escrita nos arquivos .rst que já cria um sumario
		automatico com todos os topicos(Por isto a importancia do "Titulo 1", "Titulo 2"...)

		**MAIS INFORMAÇÕES VIRAO AQUI**

3 - Após ter editado o arquivo Word iremos converter-lo atraves do script "ConversorRST". Para isto, salve o documento editado ou renomeie-o para algo mais simples e pratico.

	3.1 - Siga os passos do script e seu documento .rst sera gerado e estara na pasta "_topicos" com o nome de saida que voce mencionou.
	
4 - Abra o arquivo e use o preview para ver como a pagina iria ficar no ReadTheDocs, irão ter erros, alguns mais simples e outros mais chatos.



