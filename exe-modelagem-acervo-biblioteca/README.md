# Exercício de Modelagem Orientada a Documentos

Utilize a base de exemplo de Acervo de exemplares da UFRN - link:

http://dados.ufrn.br/dataset/06641eab-7f73-46a4-85b7-181ab55dcae0/resource/db444528-9d13-470f-a14e-e495bd886993/download/exemplares-acervo.csv

O arquivo CSV trás os dados do acervo, realize duas modelagens:

1) Relacional normalizada
2) Orientada a documentos

Implemente dois bancos de dados em MongoDB, um para cada modelo.

Monte um script de migração dos dados da tabela csv para seus bancos de dados.

Crie para ambos os modelos as seguintes consultas:

1) Listagem das dissertações do ano de 2015 a 2019
2) Total de livros com quantidade 3 ou maior no acervo, agrupado por ano
3) Todos os livros de autores que possuam a palavra Brasil.


Campos:
* registro_sistema
* titulo
* sub_titulo
* assunto
* autor
* tipo_material
* quantidade
* ano
* edicao
* editora
* isbn
* issn


