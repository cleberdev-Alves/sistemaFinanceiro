# SISTEMA FINANCEIRO - PROJETO PESSOAL!

---

## 📂 Estrutura do Projeto

```text
📂sistemaFinanceiro
├── 📂backend
│   ├── 📂API
│   ├── 📂Application
│   ├── 📂Domain
│   ├── 📂Infrastructure
│   └── 📂Tests (opcional)
│
└── 📂frontend
    ├── 📂React
    ├── 📂Components
    ├── 📂Pages
    ├── 📂Services
    └── 📂Hooks
```

---

## LEVANTAMENTO DE REQUISITO

- CALENDARIO
    - Contem os meses do ano, data de receitas e dispesas e metas.
- DESPESAS
    - Contem vencimento(parecelado ou avista), categoria, descrição, valor, tipo, observação
- INVESTIMENTOS
    - Contem descrição, tipo, data, valor inicial, valor atual, rendimento
- META
    - Contem oque deseja desse mes, limite maximo de gasto, valor para investir
- PATRIMONIO
    - Contem descrição, tipo, valor, saldo(conta corrente e dinheiro em especieis)
- RECEITA
    - Contem discrição, tipo, data, valor

### Funcionamento

O programa exibira um calendario, para o usuario se localizar e visualizar onde esta cada movimentação financeira, as depesas poderar ser cadastradas, excluidas e desativadas, podendo acrecentar e alterar os itens acima com um botao de paga ou a pagar, os investimentos poderar ser cadastradas, excluidas e desativadas, podendo acrecentar e alterar os itens acima e o valor investido entrar automaticamente no patrimonio, meta deixar voce registrar oque deseja fazer nesse mes, ano, dias e oque precisa fazer para o crescimento finaceiro, terar um campo que calculara o limite maixmo que pode ser gasto no mes de acordo com a receita recervando os 30% ou a meta que o usuario colocara separa para investir e calculara o valor que tem que ser aplicado em cada invesitimento, o patrimonio poderar ser cadastradas, excluidas e desativadas, podendo acrecentar e alterar os itens acima, tera um resumo geral do programa mensal anual, calculara automatico as despesas receitas invetimentos, as receitas poderar ser cadastradas, excluidas e desativadas, podendo acrecentar e alterar os itens acima com um botao de recebido ou a receber.

>layout desejado do dashboard
```text
_______________________________________________________
|                                   |                 |
|                                   |                 |
|       investimentos               |   patrimonio    |
|                                   |                 |
|                                   |                 |
|                                   |                 |
_______________________________________________________
|                                                     |
|              Calendario                             |
|                                                     |
_______________________________________________________
```
---

# Desejos do futuro

> Agente de controle e preenchimento pelo whatsapp com IA
> Lembrete de pagamento no email

---