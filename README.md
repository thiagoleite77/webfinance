# Gestão Financeira

Aplicação web de gestão financeira pessoal desenvolvida com HTML, CSS e JavaScript puro.

<img width="1823" height="911" alt="WEBFINANCE" src="https://github.com/user-attachments/assets/dc0eab9b-afb3-4a1c-b62d-1145f4307db1" />


O projeto tem como objetivo auxiliar no controle de receitas, despesas e investimentos, permitindo que o usuário acompanhe sua vida financeira de forma simples, visual e responsiva.

## Sobre o projeto

A aplicação foi desenvolvida para funcionar diretamente no navegador, sem necessidade de backend ou banco de dados externo neste primeiro momento.

Todos os dados são armazenados localmente no navegador através do LocalStorage, permitindo que o usuário registre e consulte suas informações financeiras no mesmo dispositivo.

## Funcionalidades

- Cadastro de receitas
- Cadastro de despesas
- Cadastro de investimentos
- Criação de categorias personalizadas
- Cadastro de lançamentos fixos mensais
- Geração automática de lançamentos recorrentes
- Filtros por período:
  - Hoje
  - Semana
  - Mês
  - Histórico completo
- Dashboard com resumo financeiro
- Cálculo automático de saldo
- Separação entre receitas, despesas e investimentos
- Gráfico de saídas por categoria
- Extrato financeiro
- Exclusão individual de registros
- Geração de PDF com insights financeiros
- Recomendações automáticas com base nos dados cadastrados
- Interface responsiva para dispositivos móveis

## Geração de PDF com insights

<img width="602" height="845" alt="Relatorio pdf" src="https://github.com/user-attachments/assets/7c947925-9efa-4f55-be49-5ec004d6ffa2" />


A aplicação possui uma funcionalidade para gerar um relatório em PDF com base nos dados financeiros cadastrados pelo usuário.

O relatório apresenta:

- Total de receitas
- Total de despesas
- Total investido
- Saldo final
- Categoria com maior gasto
- Principais saídas por categoria
- Últimos registros financeiros
- Recomendações automáticas

Os insights são gerados por meio de regras programadas em JavaScript, analisando os valores registrados no navegador.

Exemplos de análises realizadas:

- Identificação da categoria com maior gasto
- Alerta quando as despesas ultrapassam uma porcentagem elevada da receita
- Sugestão quando os investimentos estão abaixo de uma porcentagem recomendada da receita
- Alerta quando o saldo final fica negativo

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript Vanilla
- LocalStorage
- Chart.js
- jsPDF

## Armazenamento dos dados

Atualmente, os dados são armazenados no próprio navegador do usuário utilizando LocalStorage.

Isso significa que:

- Os dados permanecem salvos após atualizar ou fechar a página
- Os dados ficam disponíveis apenas no dispositivo e navegador utilizados
- Os dados podem ser perdidos caso o usuário limpe os dados do navegador
- A aplicação ainda não possui banco de dados externo
- A aplicação ainda não possui autenticação de usuários

## Estrutura do projeto

```text
gestao-financeira/
│
├── index.html
├── style.css
└── README.md
