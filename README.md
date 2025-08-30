# 🧮 Contador de Interações

Este projeto Java tem como objetivo demonstrar o uso de parâmetros via terminal, controle de fluxo com `for`, e tratamento de exceções customizadas.

## 🚀 Como funciona

O programa solicita dois números inteiros via terminal:

1. **Primeiro parâmetro**: número inicial
2. **Segundo parâmetro**: número final

Com base nesses valores, ele calcula a quantidade de interações necessárias (`segundo - primeiro`) e imprime no console mensagens como:

Imprimindo o número 1
Imprimindo o número 2...Imprimindo o número N

### ⚠️ Validação

Se o **primeiro parâmetro for maior que o segundo**, o programa lança uma exceção customizada chamada `ParametrosInvalidosException`, exibindo a mensagem:
O segundo parâmetro deve ser maior que o primeiro.

Se o **primeiro parâmetro for igual ao segundo**, o programa lança uma exceção customizada chamada `ParametrosInvalidosException`, exibindo a mensagem:
Parâmetros iguais, o segundo parâmetro deve ser maior que o primeiro.
