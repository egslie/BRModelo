# BRModelo

#Atividade Realizadas pelo BRModelo:

1.Elaborar um diagrama E-R para uma seguradora de automóveis.
Entidades: Cliente; Apólice; Carro; Acidentes.

Requisitos:
a) Um cliente pode ter várias apólices (no mínimo uma);
b) Cada apólice somente dá cobertura a um carro;
c) Um carro pode ter zero ou n registros de acidentes a ele.

Atributos:
a) Cliente: Número, Nome e Endereço;
b) Apólice: Número e Valor;
c) Carro: Registro e Marca;
d) Acidente: Data, Hora e Local;

2.Crie o modelo ER de uma empresa de Material de Construção, levando em consideração os seguintes requisitos: 
• A empresa tem um número grande de funcionários:
• identificados por uma matrícula, nome, salário, telefone. 
• A empresa armazena as informações do cliente. Cada cliente possui: 
• código para identificá-los, 
• nome completo, 
• endereço 
• telefones. 

O sistema deve armazenar as vendas realizadas: 
As vendas devem conter uma identificação, qual funcionário tirou o pedido, qual cliente, data para entrega dos produtos, local de entrega, referência para entrega. 
Os produtos podem ser identificados por nome do produto, valor unitário e quantidade.

3. O supermercado possui vários funcionários.
Os funcionários possuem no sistema os seguintes atributos: matrícula, nome, salário, telefone, cargo, data de nascimento.
As informações dos fornecedores desse supermercado são armazenadas no sistema
• O Supermercado guarda as informações de seus fornecedores. Eles identificam os fornecedores por: código para identificá-los, o nome da empresa,o endereço, telefones e pessoa de contato.

As vendas devem conter um código de identificação, qual funcionário participou dessa venda, qual a empresa que vendeu o produto, data que a mesma ocorreu.
Sobre os produtos adquiridos pelo supermercado, deseja que seja especificado um código e descrição do produto, valor unitário e quantidade.

4.Entidades: Peças, Depósitos, Fornecedor, Projeto, Funcionário e Departamento.

Requisitos: 
a) Cada Funcionário pode estar alocado a somente um Departamento; 
b) Cada Funcionário pode pertencer a mais de um Projeto; 
c) Um projeto pode utilizar-se de vários Fornecedores e de várias Peças; 
d) Uma Peça pode ser fornecida por vários Fornecedores e atender a vários Projetos; 
e) Um Fornecedor pode atender a vários Projetos e fornecer várias Peças; 
f) Um Depósito pode conter várias Peças;
g) Deseja-se ter um controle do material utilizado por cada Projeto, identificando inclusive o seu Fornecedor. Gravar as informações de data de Início e Horas Trabalhadas no Projeto.

 Atributos: 
a) Peças: Número, Peso e Cor; 
b) Depósito: Número e Endereço; 
c) Fornecedor: Número e Endereço; 
d) Projeto: Número e Orçamento; 
e) Funcionário: Número, Salário e Telefone; 
f) Departamento: Número e Setor.

5. Esta empresa está organizada em departamentos, sendo que cada projeto é sempre coordenado por um departamento. Os departamentos possuem empregados que podem ser chefes.
Embora um empregado pertença sempre a um departamento, ele pode ser alocado a projetos de outros departamentos.

6. Deseja-se projetar uma base de dados que dará suporte a um sistema WEB para controlar as horas trabalhadas pelos profissionais de uma empresa de desenvolvimento de software. O sistema destina-se a coletar dados para cobrança dos clientes da empresa. Através de um diagrama entidade-relacionamento, deve ser modelada esta base de dados. A base de dados não deve conter redundância de dados. O modelo ER deve ser representado com a notação vista em aula ou com outra notação de poder de expressão equivalente. O modelo deve apresentar, ao menos, entidades, relacionamentos, atributos, especializações, identificadores e restrições de cardinalidade. Não usar atributos multi-valorados. O modelo deve ser feito no nível conceitual, sem incluir chaves estrangeiras.

Todas atividades da empresa acontecem através de projetos. Para cada projeto, o banco de dados deve armazenar um identificador, o nome do projeto e o seu cliente. Um cliente pode ter vários projetos. Além dos projetos do cliente, o banco de dados deve armazenar o número (único) do cliente, seu CGC e seu nome. Em cada projeto são alocados vários desenvolvedores. Um desenvolvedor é alocado a um projeto por um tempo determinado (de-até). Cada desenvolvedor tem um código identificador, um nome e um custo por hora trabalhada. Para cada vez que um desenvolvedor trabalha em um projeto, mesmo que por alguns minutos, o banco de dados deve armazenar, além do projeto e do desenvolvedor, a data/hora em que o desenvolvedor começou a trabalhar e a data/hora em que ele encerrou o trabalho.

