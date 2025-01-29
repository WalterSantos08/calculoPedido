# Sistema de Cálculo de Pedidos em Java 🍔🥤

Este programa em Java calcula o total a pagar por um pedido em uma lanchonete, com base no código do item e na quantidade informada pelo usuário.

## 📝 Descrição

O programa:

1. Exibe um menu com os produtos disponíveis e seus respectivos preços.
2. Solicita ao usuário:
   - O código do item desejado.
   - A quantidade do item desejado.
3. Calcula o valor total do pedido.
4. Exibe o valor total formatado com duas casas decimais.

Caso o usuário insira um código inválido, o programa exibe uma mensagem de erro e finaliza a execução.

## 🚀 Como executar

1. Certifique-se de ter o [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) instalado em sua máquina.
2. Clone este repositório ou copie o código.
3. Compile o arquivo Java:
   ```bash
   javac calculoPedido.java
   ```
4. Execute o programa:
   ```bash
   java calculoPedido
   ```

## 🍽️ Como usar

1. Escolha um item do menu e anote seu código.
2. Digite o código do item solicitado.
3. Insira a quantidade desejada.
4. O programa calculará e exibirá o total a pagar.

### Exemplo

Entrada:

```
Tabela de preços:
1 - hot dog - R$ 4,00
2 - x-salada - R$ 4,50
3 - x-bacon - R$ 5,00
4 - torrada - R$ 2,00
5 - refrigerante - R$ 1,50

digite o codigo do item : 
2
digite a quantidade:
3
```

Saída:

```
total: R$ 13.50
```

## 📂 Estrutura do código

O código é composto por:

- **Exibição do menu**: Mostra os produtos disponíveis e seus preços.
- **Leitura dos dados do usuário**: Captura o código do produto e a quantidade desejada.
- **Cálculo do valor total**: Multiplica o preço unitário pela quantidade informada.
- **Exibição do total**: Exibe o valor total da compra formatado corretamente.
- **Validação**: Caso o código do produto seja inválido, o programa exibe uma mensagem de erro.

---


