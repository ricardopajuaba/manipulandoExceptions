# Código C# para Manipulação de Listas
* Este código em C# é um exemplo simples de como manipular exceções ao trabalhar com listas.


## Descrição do código
* O código consiste em um console application que cria uma lista de três elementos e tenta cadastrar um texto na lista. O método de cadastro lança uma exceção personalizada caso o texto seja nulo ou vazio.

* O método Main manipula as exceções que podem ser lançadas durante a execução do programa e imprime mensagens de acordo com o tipo de exceção capturada.

* O código utiliza as seguintes exceções:

IndexOutOfRangeException: lançada quando ocorre uma tentativa de acessar um índice inexistente na lista.
ArgumentNullException: lançada quando o texto a ser cadastrado é nulo ou vazio.
MinhaException: exceção personalizada criada pelo programador que é lançada quando o texto a ser cadastrado é nulo ou vazio.
Exception: exceção genérica que captura todas as exceções não tratadas pelos blocos de catch anteriores.

## Como executar o código
* Para executar o código, é necessário ter o ambiente de desenvolvimento .NET instalado na máquina. Para compilar e executar o código, basta seguir os seguintes passos:

* Abra um terminal e navegue até a pasta onde se encontra o arquivo Program.cs.
* Compile o código com o comando dotnet build.
* Execute o programa com o comando dotnet run.

## Tecnologia utilizada:

* [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/): linguagem de programação 

