Você trabalha como analista de requisitos em uma empresa contratada para desenvolver um
sistema para um restaurante, contendo as seguintes definições:
O sistema funciona internamente e online, podendo ter funcionário e cliente como usuários. Os
funcionários poderão ter as seguintes funções: gerente, caixa, garçom, cozinheiro(a) e serviços
gerais. Tanto funcionário e cliente tem acesso ao sistema com limitações por cada tipo de
usuário e função. Qualquer usuário poderá acessar o site do restaurante e se cadastrar como
cliente. A cada compra que o cliente faz no restaurante é contabilizado no seu cpf e ao atingir
10 compras no valor de mínimo R$ 20,00 cada, o cliente ganha uma refeição e uma sobremesa
grátis. Esse controle de compras por cpf deverá ser identificado como Programa de Fidelidade.
Os funcionários com funções de gerente, caixa e garçom também podem cadastrar um novo
cliente; Somente um gerente pode cadastrar qualquer outro funcionário.
O caixa será responsável por receber a comanda do cliente, finalizar a conta que consta na
comanda e registrar o pagamento da mesma. Antes de finalizar a conta, o caixa confirma se
houve alteração cadastral, como email, telefone e endereço do cliente. Se houver alteração
informada pelo cliente, o caixa já altera o cadastro e em seguida finaliza a conta e vai para a
parte de recebimento. Se o pagamento for feito com cheque, será necessário que o sistema do
restaurante se comunique com o sistema de consulta de cheques do Serviço de Proteção ao
Crédito para obter informações sobre o cliente e aguarde a resposta se o cliente é confiável ou
não para realizar esse tipo de pagamento. Se o pagamento for feito com cartão de
crédito/débito, será necessário que o sistema do restaurante se comunique com o sistema da
adquirente do cartão para obter autorização (através da maquininha de cartão). Se o
pagamento for feito por Pix, o sistema deverá solicitar o envio (upload) do comprovante do
pagamento (obtido através do próprio banco de pagamento do cliente) e o caixa deverá receber
o comprovante do cliente e inserir o comprovante no sistema. Caso o pagamento seja feito em
dinheiro, o caixa informa o valor pago em dinheiro e o sistema calcula o troco que o caixa deve
fornecer ao cliente.
Apenas o gerente terá permissão para estornar o valor pago. Somente o gerente poderá excluir
o cadastro de um usuário.
O sistema deve ter um controle da folha de pagamento e gerar holerites todo mês para cada
funcionário do restaurante, o cargo e salário de cada um é informado no momento do cadastro
e somente o gerente tem acesso à essas informações.
Somente o gerente pode editar o cargo e salário de qualquer funcionário.
Cada usuário seja ele funcionário ou cliente pode alterar o seu cadastro.
Um funcionário poderá ser cliente e vice-versa.
O sistema será responsável por enviar uma mensagem de aniversário para qualquer usuário no
dia do seu aniversário (seja criativo e elabore um cartão de aniversário para o seu usuário).
Quando um funcionário fizer aniversário de empresa, isto é, completar mais um ano da data de
admissão, o sistema deve gerar um voucher de compras da americanas, no valor de R$ 100,00
que deverá ser enviado no email de felicitação do funcionário automaticamente.

Exercícios
1 - Elabore o diagrama de casos de uso para o sistema do restaurante citado acima.
2 - Elabore o diagrama de sequência para o sistema do restaurante citado acima.
