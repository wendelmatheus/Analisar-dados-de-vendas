# Analisar dados de vendas

Antes de tudo: É necessário ter um editor de Pyhton para esse código, utilizei o Jupyter. Recomendo o Jupyter ou o Google Colab para essa aplicação.

Nesse código, o seguinte desafio foi resolvido

 Desafio:
 
 Você faz parte da equipe de Analytics de uma grande marca de vestuário com mais de 25 lojas espalhadas em Shoppings de todo o Brasil.
 
 Existem 25 lojas de uma marca de vestuário espalhadas em Shoppings de todo o Brasil.
 
 Toda semana é necessário enviar para a diretoria um ranking atualizado com 3 informações: 
 
 1- Faturamento de cada loja | 
 2- Quantidade de produtos vendidos em cada loja | 
 3- Ticket médio dos produtos da loja
 
 Além disso, é preciso enviar essas mesmas informações de cada loja individualmente (ou seja, escrever um e-mail com as informações de cada uma das lojas)
 
Observação 1: 
	Todos os dados que devem ser analisados estão na planilha "Vendas.xlsx"
	
Observação 2: 
	Para o código funcionar, o caminho da planílha deve estar especificado na linha 7
	
Observação 3:
	Na função enviar_email(), é necessário algumas configurações: 
	    linha 35: adicionar o e-mail remetente | 
	    linha 36: adicionar o e-mail destinatário |
	    linha 37: adicionar senha gerada para apps |
	    
	COMO GERAR SENHA PARA APPS (para linha 37):
	    Nesse exemplo, foi utilizado o Gmail (outros correios eletrônicos possuem outra política de segurança).
	    1- Entre no seu gmail
	    2- Clique na sua foto no canto superior direito, e em seguida clique em "Gerenciar sua Conta do Google"
	    3- Na nova aba, clique em segurança
	    OBS.: A partir daqui, é necessário estar ativado a verificação em duas etapas
	    4- Em "Como fazer login no Google", clique em Senhas de app e digite sua senha
	    5- Em "Selecionar app", escolha "E-mail", e em "Selecionar dispositivo", clique em outro e digite o nome que desejar
	    6- Finalmente, clique em gerar. Copie e cole aquela senha que aparece, e coloque na linha 37! =D
	    OBS.: Se desejar, pode apagar essa senha gerada clicando no item da lixeira que aparece na frente


