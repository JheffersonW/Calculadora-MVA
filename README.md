# Calculadora-MVA
Programa para calculo de percentual de MVA com base nos valores da Base de ICMS, IPI e Base de ST

# Calculadora de MVA (Margem de Valor Agregado)

## O que é MVA?

A MVA (Margem de Valor Agregado) é um índice utilizado para calcular o valor do ICMS (Imposto sobre Circulação de Mercadorias e Serviços) em operações interestaduais com produtos sujeitos à substituição tributária. A substituição tributária é um mecanismo onde a responsabilidade pelo pagamento do ICMS é atribuída ao fabricante ou ao importador, em vez do destinatário da mercadoria.

## Como utilizar a Calculadora de MVA?

A Calculadora de MVA foi desenvolvida para facilitar o cálculo do ICMS em operações sujeitas à substituição tributária. Siga os passos abaixo para utilizá-la corretamente:

1. **Selecionar o Modo de Cálculo:**

   - Escolha o modo de cálculo que permitirá ou bloqueará a inserção do valor de IPI (Imposto sobre Produtos Industrializados) do produto. Algumas operações podem incluir o valor do IPI na base de cálculo do ICMS, enquanto outras não.

2. **Informar o Valor da Base de ICMS:**

   - Insira o valor da base de cálculo do ICMS sobre o qual o imposto será aplicado. Essa base pode variar dependendo das regras fiscais e do valor do produto.

3. **Informar o Valor de IPI (Opcional):**

   - Caso o modo de cálculo selecionado permita a inclusão do IPI na base de cálculo do ICMS, informe o valor do IPI correspondente.

4. **Informar o Valor Base de ST:**

   - Forneça o valor base para o cálculo da substituição tributária (ST). Esse valor pode incluir o preço do produto, o frete, o seguro e outras despesas.

5. **Clicar em Calcular:**

   - Após preencher os campos necessários, clique no botão "Calcular". O sistema irá processar as informações e calcular o percentual de MVA aplicável na operação.

6. **Mensagem de Alerta:**

   - Após o cálculo, o sistema exibirá uma mensagem de alerta ao usuário, mostrando o percentual de MVA calculado para a operação. Esse valor será utilizado para determinar o ICMS a ser pago na substituição tributária.

7. **Botão de Limpar:**

   - Caso deseje recalcular ou inserir novos valores, utilize o botão "Limpar" para apagar todos os dados dos campos preenchidos.

```python
# Nota: Se o usuário clicar em "Calcular" sem informar todos os valores obrigatórios, 
# receberá uma notificação de erro e será redirecionado para o campo específico que necessita ser preenchido.
# Certifique-se de fornecer todas as informações necessárias antes de prosseguir com o cálculo.
```
