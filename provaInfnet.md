Questao 1

Questao 2
SELECT  Customers.CustomerName, Orders.OrderID, Products.SupplierID, Suppliers.Country, Suppliers.SupplierID 
FROM Orders, Products, Suppliers
INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID AND Products.SupplierID = Suppliers.SupplierID WHERE Suppliers.Country = 'Brazil';

Questao 3
  a - Arquivos de template são arquivos já prontos para ser usados, e você apenas altera o que você quer para o seu site.
  b - Tema filho é como se fosse classes filhas, ou seja, esse tipo de tema herda funcionalidades de outro tema, chamado de tema pai.
  c - Esse template é responsável por listar todos os posts do site.
  d - A função dele é mostrar um post ou até mesmo uma pagina do seu site.
  
Questao 4
  Criaria uma pasta generica e nela montaria o site de acordo com a minha linguagem, a partir disso criria outras pastas de acordo com cada regiao do mundo. Por exemplo, br (brasil), us (Estados Unidos), pt (Portugal). E nessas pastas eu copiaria tudo que houver na pasta generica, mudando somente a lingua de acordo com cada região. Usaria uma API do google onde ele identifica a sua localização e muda para a pasta (url) da sua região.
