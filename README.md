O sistema do Júnior tem como objetivo desenvolver um sistema que funcione como uma loja virtual.


Para cada cliente, releia as anotações da sua entrevista (Atividade 02) e identifique:

Entidades: Quais são as "coisas" que precisam ser salvas? (Ex: Cliente, Produto, Consulta).
-> O cliente, o produto e os pedidos devem ser salvos.

Atributos: Quais dados cada entidade tem? (Ex: Nome, CPF, Preço, Cor).
Cliente -> id, nome, cpf, email e telefone
Pedidos -> id_pedido, id_cliente e id_produto
Produto -> id, nome e preco

Relacionamentos: Como elas se conectam? (Ex: 1 Paciente agenda N Consultas).
-> 1 Cliente faz N Pedido e Pedido contém 1 Produto.

![Diagrama DER](./der-geek/der-geek-novo.drawio.png)