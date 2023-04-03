<h2>Introdução</h2>

Olá! Vou deixar a você, leitor, um pequeno tutorial de como rodar esse simples (mas efetivo) arquivo CRUD no seu PC.<br>

CRUD são as quatro operações básicas de um projeto que tem conexão com banco de dados (Create-criar, Read-ler, Update-atualizar e Delete-deletar).<br>
Esse projeto é um simples controlador de banco de dados, que dispõe dessas quatro funções de uma forma intuitiva.

Para testes, utilizaremos o endereço de IPv4 "127.0.0.1", que refere-se ao seu próprio host. Nos instaladores das ferramentas que indicarei a seguir, não mude este número, se houver tal opção em algum deles.<br>

<h2>Vamos aos trabalhos?</h2>
<h3> Xampp - conexão para teste </h3>
Primeiramente, você deve configurar o banco de dados em si. Escolha o seu gerenciador de databases favorito(mysql, heidisql, entre outros)!
Caso não tenha instalado nenhum deles, aqui está o link do HeidiSql:
https://www.heidisql.com/download.php <br><br>

Precisaremos também do aplicativo xampp, que permitirá a criação de uma conexão para testes. Você pode instalar ele nesse link abaixo:
https://www.apachefriends.org/pt_br/download.html <br>

<b>Instale e abra o xampp, ligando as funções do Apache e MySql, como no exemplo a seguir:</b><br>

![crudttr1](https://user-images.githubusercontent.com/105890630/228091860-457b800c-14c2-4fd5-a796-9e05ec014ec7.png)<br>

<b>Clique nos dois botões destacados acima!</b>


![crudttr](https://user-images.githubusercontent.com/105890630/228091889-5375746e-7eea-4010-9ce2-96e41a83aa7b.png)<br>

<b>Se estiver como na foto, estará funcionando!</b><br>

  <h2> Sql - gerenciador do banco </h2>
<b>em seguida, abra o HeidiSql e crie uma nova sessão:</b><br><br>


![ttrheid](https://user-images.githubusercontent.com/105890630/228086603-84950eaf-9e3c-4053-9c63-404af5451554.png)<br>


<b>Após criar a sessão e abrí-la, vá para a aba de consulta</b><br><br>

![cnsltttr](https://user-images.githubusercontent.com/105890630/228091141-afabbec0-4d4f-4d24-b4c2-b1e6b4310fe0.png)<br>

<b>No espaço para digitar a consulta, cole o código do arquivo "backupescola.sql", que está localizado aqui no projeto, na pasta models.</b><br>
<h2>Toques finais</h2>
Agora, vá ao explorador de arquivos, entre em Disco local C:/, então abra a pasta xampp e entre em htdocs. Lá <b>você deve extrair e colar a pasta desse projeto!</b><br>



![pastattr](https://user-images.githubusercontent.com/105890630/228385608-79f49ac8-e032-4aea-8a25-ea8ef40d1265.png)<br>

<b>Visualize o local da pasta "exemplo-crud-main", é dessa forma que deve ficar.</b><br>

Após isso, basta ir ao seu navegador e digitar na barra superior o caminho "localhost/exemplo-crud-main". <br>
<b>O site se apresentará na sua tela da seguinte forma forma:</b><br>

![image](https://user-images.githubusercontent.com/105890630/228392239-6d672db1-320c-41b1-bb6a-bc732daf50ea.png)<br>

<b>Parabéns! Agora você pode inserir, editar, consultar e deletar informações nesse banco de dados.</b><br>

<h2>Considerações finais</h2>
Muito obrigado por utilizar o meu código! Sinta-se livre para fazer sua própria versão dele, submetendo-o às alterações que julgar necessárias. Eu recomendo que utilize o visual studio para tais modificações.<br><br>
Muito obrigado pela atenção!



  
