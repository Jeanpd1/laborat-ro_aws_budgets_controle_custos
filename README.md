# Laboratório AWS: Controle de Custos com AWS Budgets

Este projeto documenta a criação de um orçamento na AWS utilizando o serviço **AWS Budgets**. O objetivo é configurar um mecanismo de controle para monitorar os gastos e receber alertas automáticos, uma prática essencial de gestão financeira na nuvem (FinOps) para evitar surpresas na fatura.

-------------------------------------------

## Requisitos

- Uma conta registrada na [![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com)
------------------------------------------------------
<br>

## Configuração do Orçamento

O laboratório consistiu na configuração de um orçamento com as seguintes especificações:

* **Nome do Orçamento:** meu-budget-seu-nome
* **Valor Orçado:** US$ 10,00
* **Tipo de Alerta:** Acionado por percentual do valor orçado
* **Limite do Alerta:** 10%
* **Acionador:** Custo real
* **Destinatário de E-mail:** exemplo@exemplo.com

### Print da Tela de Configuração Inicial
![Escolha do tipo de orçamento](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/1-Escolher%20tipo%20de%20or%C3%A7amento.png?raw=true)
![Definição de detalhes e período](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/3-Definir%20valor%20do%20or%C3%A7amento.png?raw=true)
![Definição do valor e escopo](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/4-Escopo%20do%20or%C3%A7amento.png?raw=true)

### Print da Configuração do Alerta
![Definição das opções avançadas](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/5-Op%C3%A7%C3%B5es%20avan%C3%A7adas.png?raw=true)
![Configuração do Alerta #1 com limite de 10%](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/6-Valor%20do%20or%C3%A7amento.png?raw=true)
![Configuração inicial com modelo simplificado](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/2-Nome%20do%20or%C3%A7amento.png?raw=true)
![Resumo do Alerta #1 após configuração](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/7-Alert%231.png?raw=true)


### Print do Orçamento Criado na Visão Geral
![Página principal do orçamento criado](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/8-principal%20budget.png?raw=true)
![Aba de Alertas mostrando o status](https://github.com/Jeanpd1/laborat-ro_aws_budgets_controle_custos/blob/main/Prints/9-Alerta.png?raw=true)


## Conclusão

Configurar um orçamento na AWS é uma ferramenta proativa e essencial. Permite ganhar visibilidade sobre os gastos e, crucialmente, ser alertado antes que os custos ultrapassem limites definidos. Esta prática transforma o gerenciamento financeiro de reativo (descobrir o gasto no final do mês) para proativo (monitorar e agir enquanto o gasto acontece), sendo uma camada fundamental de controle para manter os custos na nuvem sob controle.
