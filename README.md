# fatura-py
Código feito em Python para listar e somar preço de produtos com determinadas condições de desconto e parcelamento.

Esse projeto tem o intuito de usar noções e laços de programação em Python.

O objetivo deste trabalho é calcular o custo final de uma compra. A entrada começa com um número N,
que é o número de produtos que será lido da entrada. Depois, para cada um dos N itens, os seguintes
dados serão apresentados, um por linha. E por útimo, recebe uma string "sim" ou "nao" confirmando se haverá desconto
As regras são:
O custo de um produto é calculado como a multiplicação da sua quantidade pelo seu preço
Caso o produto esteja em promoção, deve-se avaliar as seguintes condições:
Caso sejam comprados 1, 2, 3, ou 4 itens do mesmo produto, nenhum desconto será concedido;
Caso sejam comprados 5, 6, 7, 8, ou 9 itens do mesmo produto, deve-se aplicar um desconto de 10% nesse produto;
Caso sejam comprados 10 ou mais itens do mesmo produto, deve-se aplicar um desconto de 15% nesse produto.
No final, será mostrado a somatória dos produtos, e se o valor execer R$1000,00, mostrará "A compra pode ser parcelada"
