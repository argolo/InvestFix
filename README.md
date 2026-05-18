# InvestFix

Uma ferramenta simples, moderna e responsiva para comparar investimentos de renda fixa diretamente no navegador.

O objetivo do **InvestFix** é ajudar investidores pessoa física a comparar rapidamente diferentes opções de renda fixa, simulando rentabilidade líquida, imposto de renda, valor final e outros indicadores importantes.

---

## ✨ Funcionalidades

* Comparação de múltiplos investimentos simultaneamente
* Lista dinâmica de investimentos
* Cálculo automático de:

  * Rentabilidade bruta
  * Resultado líquido
  * Imposto de renda regressivo
  * Valor final
* Suporte para:

  * CDB
  * LCI
  * LCA
  * CRI
  * CRA
  * LIG
  * Debêntures
* Identificação automática de investimentos com cobertura FGC
* Indicadores econômicos editáveis:

  * CDI
  * SELIC
  * IPCA
* Tema Dark / Light

  * automático pelo sistema operacional
  * com alternância manual
* Persistência automática via `localStorage`
* Layout responsivo
* Tudo em um único arquivo HTML
* Sem dependências externas

---

## 🧮 Regras de cálculo

### IR regressivo

| Prazo             | IR    |
| ----------------- | ----- |
| Até 180 dias      | 22,5% |
| 181 a 360 dias    | 20%   |
| 361 a 720 dias    | 17,5% |
| Acima de 720 dias | 15%   |

### Investimentos isentos

Os seguintes investimentos não possuem cobrança de IR:

* LCI
* LCA
* CRI
* CRA
* LIG
  
---

## 🛡️ Cobertura FGC

O InvestFix identifica automaticamente ativos com cobertura do Fundo Garantidor de Créditos.

### Cobertos automaticamente

* CDB
* LCI
* LCA

---

## 💾 Persistência local

Todos os dados são salvos automaticamente no navegador usando `localStorage`.

Isso inclui:

* investimentos cadastrados;
* configurações econômicas;
* preferência de tema.

---

## 🚀 Como usar

1. Baixe o arquivo HTML
2. Abra no navegador
3. Comece a adicionar investimentos

Nenhuma instalação é necessária.

---

## 📁 Estrutura do projeto

```text
investfix/
└── index.html
```

---

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript Vanilla

Sem frameworks.

---

## 📱 Responsividade

O layout foi desenvolvido para:

* desktop
* tablets
* smartphones

As linhas de investimentos permanecem lineares, com scroll horizontal controlado em telas menores.

---

## 🔒 Privacidade

O InvestFix:

* não envia dados para servidores;
* não possui backend;
* não coleta informações do usuário.

Todos os dados permanecem localmente no navegador.

---


## 👨‍💻 Autor

projetado por
[argolo.dev](https://argolo.dev?utm_source=chatgpt.com)
