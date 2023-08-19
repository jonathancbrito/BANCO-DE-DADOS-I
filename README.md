# BANCO-DE-DADOS-I
Material de Avaliação Prática - BANCO DE DADOS I - Engenharia de Software 07/2023
#
QUESTÃO 1
#
Empresa de aluguel de carros
 
Uma empresa de aluguel de carros solicita que você faça a modelagem de dados para iniciar o seu projeto de software. Nesta empresa os clientes podem alugar carros por um determinado período, com diferentes modelos e categorias disponíveis. Para gerenciar essas informações, a empresa precisa de um banco de dados que permita armazenar e consultar dados sobre clientes, carros, locações, pagamentos e filiais. A empresa mantém um registro de clientes no qual armazena as informações sobre os clientes que alugam carros com os dados de nome, sobrenome, CPF, data de nascimento, endereço, telefone e e-mail. Além dos clientes, a empresa também possui uma frota de carros com as informações sobre os carros disponíveis para aluguel, em que cada carro possui informações de modelo, ano, cor, categoria (exemplo: econômico, luxo, SUV), placa e preço por hora/dia.

Quando é realizada uma locação de veículo pelo cliente, são registrados os dados de data de início, data de fim, carro alugado, cliente que realizou a locação e filial em que o carro foi retirado. Após a locação é realizado o pagamento. As informações de pagamentos são valor, forma de pagamento (exemplo: cartão de crédito, dinheiro, débito), data do pagamento e locação correspondente. É importante ressaltar que uma locação pode ter mais de uma forma de pagamento. Ainda no controle da filial, são mantidas as informações de nome, endereço, telefone e e-mail.

Vale considerar que um cliente pode realizar várias locações, assim como um carro pode ser locado várias vezes pelo mesmo cliente ou por clientes diferentes. Contudo, não pode ser locado por das pessoas no mesmo período. Cada filial possui sua própria frota de carros disponíveis para aluguel. Uma locação é realizada por um único cliente em uma única filial. Um pagamento é realizado para uma única locação de carro.

Com esse modelo, a empresa seria capaz de gerenciar informações sobre seus clientes, carros, filiais, locações e pagamentos de maneira eficiente e organizada.
 
Para esta atividade MAPA, crie o Diagrama de Entidade Relacionamento para este projeto, levando em consideração os seus estudos da disciplina. Lembre-se que no Diagrama deverá constar em um retângulo a entidade, atributos com seus respectivos tipos e as relações.
