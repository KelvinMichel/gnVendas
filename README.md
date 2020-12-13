# gnVendas
Desafio Técnico
Este desafio propõe a criação de um sistema de vendas que será chamado de Gn-Vendas.

Requisitos mínimos
Os requisitos mínimos são listados abaixo.
 
1 Cadastro de produtos
O Gn-Vendas deve ter uma página para cadastro de produtos.
•	O produto deve ter nome e valor em reais;
·         Os produtos devem ser salvos na tabela produtos ;
·        Todos os campos do formulário devem ser validados no frontend e no backend; Não é necessário proteger a página utilizando login e senha;
2  Listagem de produtos
O Gn-Vendas deve ter uma página para listar os produtos cadastrados.
·         Todos os produtos devem ser listados na página;
·         Cada produto deve ter um botão Comprar;
·         A página deve ter um formulário que solicite Nome , CPF e Telefone do comprador;
3  Compra de produtos
·        Ao clicar em Comprar, um boleto Gerencianet ¹ deve ser gerado para o 
comprador; O boleto deve ter vencimento para 2 dias após a compra ²;
·         As compras devem ser registradas em uma tabela chamada compras ;
·        O link do PDF ³ e o ID do boleto ⁴ devem ser salvos na tabela compras após a geração do boleto; Todos   os campos do formulário devem ser validados   no frontend e no  backend;
·         Não é necessário proteger a compra utilizando login e senha;


Critérios de aceitação
·         O banco de dados deve ser MySQL;
·         A linguagem pode ser PHP ou Node.js;
·         O frontend deverá usar HTML, CSS e JavaScript;
·        O material entregue deve ter um arquivo README.md contendo as instruções para instalação e execução do projeto; O uso de bibliotecas está liberado;


Materiais de apoio
1. API Gerencianet: https://dev.gerencianet.com.br/docs/gerar-boleto-bancario
2. Vencimento = expire_at
3. Link do PDF = pdf.charge
4. ID do boleto = charge_id


Credenciais da API Gerencianet
As credenciais abaixo poderão ser usadas para fazer a integração com a API da Gerencianet para geração de boleto.
Client_Id_4e4327e045ceb277ed5f62db8c46c399c309e0bf
Client_Secret_bb1ad596c70e1c17089cd27ec860816670412681
 
