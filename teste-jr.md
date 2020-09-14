### Questão 1
Analise o processo descrito abaixo e modele-o utilizando BPMN 2.0. Modele o processo da
forma achar melhor e caso tenha dúvidas ou considerações, faça anotações como
se fosse levá-las para uma reunião com o cliente.

Um representante de vendas envia uma oferta de financiamento para um cliente potencial e aguarda uma resposta. 
Caso o cliente responda recusando a oferta, os dados da proposta são atualizados e então arquivados. Se o cliente 
responder positivamente à oferta e anexar todos os documentos necessários, então a proposta segue para a administração
para ser concluída. Na administração, caso exista a necessidade de algum documento não fornecido, uma mensagem é gerada 
e enviada para o cliente requisitando os documentos necessários. Se nenhuma resposta é recebida após duas semanas, 
a proposta tem seus dados atualizados e então é arquivada.


### Questão 2

Dadas as tabelas abaixo, monte as consultas SQL solicitadas:

Tabela 1 - ```autores```  possui mais de 1 milhão de linhas, 
aqui estão as 6 primeiras linhas

| nome_autor | id_livro   |
|------------|------------|
| autor_1    | livro_1    |
| autor_1    | livro_2    |
| autor_2    | livro_3    |
| autor_2    | livro_4    |
| autor_2    | livro_5    |
| autor_3    | livro_6    |
| ...        | ...        |


Tabela 2 - ```livros``` possui mais de 1 milhão de linhas, 
aqui estão as 6 primeiras linhas

| id_livro   | copias_vendidas | data_lancamento |
|------------|-----------------|-----------------|
| livro_1    | 1000            | 20/01/1996      |
| livro_2    | 300             | 20/01/2001      | 
| livro_3    | 900             | 20/01/2017      |
| livro_3    | 1200            | 20/01/2003      |
| livro_3    | 750             | 20/01/2010      |
| livro_3    | 3500            | 20/01/1998      |
| ...        | ...             | ...             |


1. Listar o livro que mais vendeu cópias
2. Listar todos os autores com um ou mais livros que venderam mais de 10.000 cópias
3. Listar os 3 livros com menor volume de cópias vendidas
4. Listar todos os livros publicados entre os anos de 2000 e 2010
5. Listar os 3 autores com mais livros publicados
6. Listar os 3 autores com mais copias vendidas e a quantidade de cópias que cada um vendeu (somando todos seus livros)

