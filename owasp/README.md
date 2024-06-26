# 🍔 Fast & Foodious - OWASP ZAP Report

- [OWASP ZAP Report](#owasp-zap-report)
  - [Relatórios por Microserviços](#relatorios-por-microservicos)
    - [fast-n-foodious-ms-produto](#fast-n-foodious-ms-produto)
    - [fast-n-foodious-ms-pedido](#fast-n-foodious-ms-pedido)
    - [fast-n-foodious-ms-pagamento](#fast-n-foodious-ms-pagamento)
    - [Conclusão](#conclusao)

## Relatórios por Microserviços

### fast-n-foodious-ms-produto
- **Cardapio de produtos**
  ![cardapio de produtos](png/a-cardapio-produtos-2024-03-03-report.png)
  [Link para relatório completo ](pdf/a-cardapio-produtos-2024-03-03-report.pdf)

### fast-n-foodious-ms-pedido
- **Realizacao do pedido (checkout)**
  ![Realizacao do pedido (checkout)](png/b-realizacao-do-pedido-checkout-2024-03-03-report.png)
  [Link para relatório completo](pdf/b-realizacao-do-pedido-checkout-2024-03-03-report.pdf)

### fast-n-foodious-ms-pagamento
- **Geracao do Pagamento**
  ![Geracao do Pagamento](png/c-geracao-do-pagamento-2024-03-03-report.png)
  [Link para relatório completo](pdf/c-geracao-do-pagamento-2024-03-03-report.pdf)

  - Este endpoint retorna dados do pagamento referente ao ID do pedido, incluindo o `transacaoId` que sera utilizado para confirmacao do pagamento.

- **Confirmacao do Pagamento:**
  ![Confirmacao do Pagamento](png/d-confirmacao-do-pagamento-2024-03-03-report.png)
  [Link para relatório completo](pdf/d-confirmacao-do-pagamento-2024-03-03-report.pdf)

  - Este endpoint confirmara o pagamento do pedido, e ira atualizar o pagamento para `CONFIRMADO = 1` ou `REJEITADO = 2`

## Conclusão
**Nenhuma ação/atualização posterior as análises foi necessária, uma vez que não foram encontradas ameaças de risco alto** pela ferramenta OWASP ZAP. Portanto, os relatórios foram extraídos apenas uma vez para cada serviço.