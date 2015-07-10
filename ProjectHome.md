Prova 2 de PHP do Alcides Maya



Gerenciamento de contas bancárias.

A prova consitirá na criação de uma base de dados e implementação de um mini sistema para manipular contas correntes.

Totas as transações devem ser gravadas no banco de dados.

Serão considerados os seguintes critérios para avaliação (todos devem ser respeitados para evitar a perda de pontos):
> Não utilização de programação procedural<br>
<blockquote>Encapsulamento<br>
Herança<br>
Polimorfismo<br>
Abstração<br>
Método estático<br></blockquote>

A prova pode ser feita em dúplas.<br>
<br>
ATENÇÃO PARA A ENTREGA:<br>
<blockquote>A entrega deve ser feita OBRIGATORIAMENTE via e-mail até sexta-feira, 22 de outubro as 18hs.<br>
Provas recebidas após esta data e horário terão desconto de 1 ponto na nota final da avaliação.<br>
O e-mail de entrega DEVERÁ conter o nome da pessoa ou dupla NO CORPO do e-mail.<br>
O assunto DEVE ser AV2/LP2/2EWN-0210.<br>
Compacte o código e a base de dados e anexe ao e-mail.<br>
Email para entrega: stratu@gmail.com<br>
Alunos que ficarem em recuperação serão avisados via e-mail e deverão implementar durante a próxima aula as correções que forem especificadas no e-mail de resultado. Os alunos que não ficarem em recuperação estão dispensados da próxima aula.</blockquote>


DADOS DA PROVA<br>
<br>
Tabela de clientes<br>
<blockquote>código<br>
nome<br>
endereço completo (desmembre os campos)<br>
data de nascimento<br>
cpf<br>
rg<br></blockquote>

Tabela de contas correntes<br>
<blockquote>agência<br>
número<br>
cliente<br>
saldo<br>
limite<br>
data de abertura<br></blockquote>

Tabela de contas poupança<br>
<blockquote>agência<br>
número<br>
cliente<br>
saldo<br>
data de aniversário<br>
data de abertura<br></blockquote>

1pt - Implemente a base de dados e conecte utilizando a classe DB utilizada em aula<br>
<br>
1pt - Crie uma classe para clientes chamada "Cliente" (não é necessário implementar os métodos de edição e remoção)<br>
<br>
1pt - Crie uma classe genérica de contas bancárias chamada "Conta".<br>
<blockquote>Esta classe deve obrigar a criação dos métodos Deposito, Retirada e Cadastro nas suas classes filhas</blockquote>

2pt - Crie uma classe para contas correntes chamada "ContaCorrente"<br>
<blockquote>A conta corrente deve contemplar limite (saldo negativo)<br>
Lembre-se que o método de retirada deve considerar o limite da conta corrente</blockquote>

2pt - Crie uma classe para contas poupança chamada "ContaPoupanca"<br>
<blockquote>A conta poupança deve contemplar data de aniversário<br>
Implemente um método chamado RendimentoPoupanca que deve comparar a data atual com a data de aniversário das poupanças. Se for o mesmo dia, deve aumentar o saldo da poupança em 1.2%</blockquote>

1pt - Implemente as talas que irão cadastrar clientes, contas correntes e contas poupança.<br>
<br>
2pt - Implemente uma tela onde o cliente poderá fazer retiradas ou depósito na conta corrente ou poupança