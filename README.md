# Aplicando Testes Unitários

## Unit Testing - Conversão de Temperatura

Neste primeiro teste, foi selecionado 6 grupos de valores para testar o algoritmo de conversão de temperatura, foi passado o valor em celsius esperado e o valor em Fahrenheit, sendo que o retorno da função deveria ser o valor em celcius passado, o que de fato aconteceu.

### Usando xUnit

![alt text](image.png)

### Usando NUnit

![alt text](image-1.png)

### Usando MSTest

![alt text](image-2.png)

## Unit Testing - Fluent Assertions

Neste teste, foi utilizado Mock Objects para realizar testes unitários de consulta de crédito, mockando a implementação de CPF_INVALIDO, CPF_ERRO_COMUNICACAO, CPF_SEM_PENDENCIAS e CPF_INADIMPLENTE, garantindo que seja possível testar as entradas e saídas sem realizar a implmentação completa das funcionalidades.

### Usando xUnit + Moq

![alt text](image-3.png)

### Usando xUnit + NSubstitute

![alt text](image-4.png)
