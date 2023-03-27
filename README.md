# Alura Pets / POWER BI
<h2>Projeto desenvolvido durante a formação de Power BI da plataforma Alura </h2>


<p>
O primeiro projeto foi a realização de um dashboard para um Pet-Shop, a ideia principal era colocar em evidência o faturamento da loja.
</p>

![image](https://user-images.githubusercontent.com/128874237/228070868-12773585-65dc-4784-93c0-134483388827.png)
<br>

<p> Foram utilizados Cartões para representar os valores únicos como "Faturamento Total", "Quantidade de produtos vendidos", e uma "Média de Pets/Clientes"; </p>

![image](https://user-images.githubusercontent.com/128874237/228075331-22565eb1-a7eb-4d4e-be71-15c6715480c0.png)
![image](https://user-images.githubusercontent.com/128874237/228075471-5f527659-972a-4887-b47d-7482710e7bd2.png)
![image](https://user-images.githubusercontent.com/128874237/228075603-5ff25c5d-832d-446d-a513-17fcbd47ea45.png)
![image](https://user-images.githubusercontent.com/128874237/228072972-8a8cea4a-29a0-4fa4-bdb9-78581ef3e28e.png)
<br>

<p> Logo a direita, foi realizado um campo com a data de compra, sendo possível filtrar por um determinado período. Foi realizado com uma simples segmentação de dados, incluindo como valor as colunas de "Data de compra". </p> 

<br>

<p> O mesmo serve para a seleção do campo "Marca" logo ao lado, possibilitando uma filtragem por uma marca específica de produtos da loja. Também foi realizado com uma segmentação de dados, porém no campo de valores, foi selecionado a coluna contendo as marcas de fato.

![image](https://user-images.githubusercontent.com/128874237/228074920-a85d9440-6aa9-4855-847b-e98dcc51b9ba.png)
![image](https://user-images.githubusercontent.com/128874237/228074796-75261d2a-8bb9-44fb-a157-2e8aa18e2466.png)
![image](https://user-images.githubusercontent.com/128874237/228075083-96d225f3-09b7-4315-900c-742c4332409c.png)

<br>
  
<p> Para desenvolver uma visualização de faturamento dividido por gênero, foi solicitado um gráfico de pizza, onde os parâmetros seriam o Gênero, e a Soma do Faturamento. (não costumo utilizar esse tipo de gráfico) </p>

![image](https://user-images.githubusercontent.com/128874237/228077328-2e287278-2e15-4b72-b717-f6261168a043.png)
![image](https://user-images.githubusercontent.com/128874237/228077128-8eb64982-750f-4f1e-805a-45534ee2ef69.png)

<br>

<p> Para representar o faturamento total por bairro, foi selecionado um gráfico de barras clusterizado, possibilitando uma visualização simples e objetiva. Foram utilizados como parâmetros o Bairro no Eixo Y, e o Faturamento total no Eixo X. </p>

![image](https://user-images.githubusercontent.com/128874237/228077816-7c0dc100-c151-46da-a29b-b87df272832f.png)
![image](https://user-images.githubusercontent.com/128874237/228077890-a8c60996-7dc0-435e-b1a5-ed28b3313ea8.png)

<p> Para a realização da visualização do faturamento total por mês e ano, foi escolhido um gráfico de área, que combina muito com esse tipo de informação, nos permitindo visualizar muito bem a evolução com o passar do tempo. Como parâmetros para esse modelo de visualização, teremos as Datas e novamente o Faturamento total.

![image](https://user-images.githubusercontent.com/128874237/228079439-67e8b555-62d0-4375-8458-b3da96a87f24.png)
![image](https://user-images.githubusercontent.com/128874237/228079336-50fed7c0-6621-4da5-ad00-7045a76100fe.png)

<p> Por último, mas não menos importante, temos a visualização por produto. Fou utilizado um "Text Filter" para realizar a filtragem. Logo abaixo temos a opção de clicar na imagem do produto para uma pesquisa mais interativa que foi feita utilizando o Image Grid, que utilizam como parâmetro a URL do item. Para isso basta ter em alguma das tabelas a url referente a imagem dos produtos. </p>

![image](https://user-images.githubusercontent.com/128874237/228079965-5e58e7dd-4401-4e3e-9f38-b968fa949689.png)

<p> Ao selecionar um dos produtos, ele demonstra em todos os gráficos o valor respectivo aquele item, alterando também os valores nos cartões, permitindo uma análise item a item para verificar o rendimento. </p>

![image](https://user-images.githubusercontent.com/128874237/228080349-5f8fcdc3-9f8a-41ae-a7dc-922efecf9c6f.png)

<p> Lembrando que essa conexão entre os gráficos só pode ser realizado com as conexões estratégicas do modelo. Nesse projeto realizamos relações entre três tabelas, que possuiam a mesma informação. Segue exemplo:

![image](https://user-images.githubusercontent.com/128874237/228080678-1800fd1e-02f7-479e-8e7c-eb125f0914d3.png)











