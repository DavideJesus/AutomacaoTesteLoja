# Automação de Teste: Efetuar compra com sucesso


### O script a seguir trata da automação de um teste que efetua uma compra de modo que tenha sucesso.


O srcipt realiza os seguintes passos:

1. Acessa o site: http://automationpractice.com/index.php
2. Escolhe um produto qualquer na loja.
3. Adiciona o produto escolhido ao carrinho.
4. Prossegue para o checkout.
5. Valida se o produto foi corretamente adicionado ao carrinho e prossegue caso esteja tudo certo.
6. Realiza o cadastro do cliente preenchendo todos os campos obrigatórios dos formulários.
7. Valida se o endereço está correto e prossegue.
8. Aceita os termos de serviço e prossegue.
9. Valida o valor total da compra.
10. Seleciona um método de pagamento e prossegue.
11. Confirma a compra e valida se foi finalizada com sucesso.


__Para testar, basta baixar o arquivo repositório, descompactá-lo, abri-lo dentro do software IntelliJ IDEA e o executar.__


**_*Construção:_**

**Software:**
- IntelliJ IDEA
- Google Chrome (auxílio do ChromeDriver)
- SO Windows
 
**Estrutura e linguagem:**
- Java
- Maven
- Selenium
- JUnity
- PageObject
