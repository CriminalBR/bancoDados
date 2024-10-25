#SELECT max (Valor_unitario) FROM produto;
#SELECT COUNT(*) FROM produto WHERE = 0
#SELECT COUNT(*) FROM Pedido WHERE DATA LIKE '2024-09-%';
#SELECT nome FROM vendedor WHERE ID= (SELECT ID_vendedor FROM pedido WHERE DATA='2024-10-03';
#SELECT COUNT(*) FROM pedido WHERE DATA LIKE'2024-09-%' AND ID_vendedor = (SELECT ID FROM vendedor WHERE nome = 'Breno Ferraz');
#SELECT nome FROM produto WHERE id = 
#(SELECT id_produto FROM produto_pedido WHERE qtd > 4 AND valor_total > R$ 50)
