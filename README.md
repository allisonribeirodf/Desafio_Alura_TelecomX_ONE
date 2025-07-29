# Desafio_Alura_TelecomX_ONE

# 🔍 Análise de Evasão de Clientes – **Telecom X**

Projeto de análise de dados desenvolvido como parte de um desafio da Alura, com foco na identificação de padrões de **churn** (evasão de clientes) em uma empresa fictícia de telecomunicações.

---

## 📌 Objetivo

Compreender os principais fatores associados ao cancelamento de contratos e propor estratégias baseadas em dados para **redução da evasão** e **retenção de clientes**.

---

## 📊 Principais Análises

### 📁 Análise Categórica

- **Tipo de Contrato**  
  Clientes com contrato mensal apresentam maior taxa de churn.  
  Já contratos de 1 ou 2 anos demonstram maior estabilidade.

- **Forma de Pagamento**  
  Pagamentos via *Electronic Check* estão mais associados à evasão.  
  Métodos automáticos (cartão, débito) reduzem significativamente o churn.

- **Relacionamentos Pessoais**  
  Clientes sem dependentes ou parceiro(a) tendem a cancelar com mais frequência.

- **Gênero**  
  Não houve influência significativa – distribuição equilibrada entre homens e mulheres.

---

### 📈 Análise Numérica

Variáveis analisadas:

- `tenure` (meses de contrato)
- `TotalCharges` (gasto total)
- `MonthlyCharges` (mensalidade)
- Gasto diário estimado (Total / Tenure)

**Padrões identificados:**

- Clientes que cancelam costumam ter menos tempo de vínculo.
- O gasto total é menor entre churners, indicando saída precoce.
- Em muitos casos, churners tinham mensalidade mais alta → sensibilidade a preço.

---

## 💡 Insights Relevantes

- **Churn alto** entre clientes recentes, sem dependentes ou parceiro(a), e com contrato mensal.
- **Pagamentos manuais** estão ligados a maior evasão.
- Clientes antigos e com gasto acumulado maior tendem a ser mais fiéis.

---

## ✅ Recomendações Estratégicas

- 🎁 Oferecer **benefícios nos primeiros meses** de contrato.
- 🔒 Estimular **contratos de maior duração** com vantagens exclusivas.
- 💳 Incentivar **pagamentos automáticos** com cashback ou desconto.
- ⚠️ Monitorar clientes com **mensalidade alta e pouco tempo de casa**.
- 🚨 Implementar **alertas internos** para perfis com fatores combinados de risco.

---

## 🔚 Conclusão

Compreender o comportamento dos clientes que cancelam permite direcionar ações assertivas e prevenir a evasão.  
Os dados mostram que **tempo de vínculo, perfil familiar e método de pagamento** são fatores-chave.  

📈 **Próximo passo sugerido:** Construção de modelos preditivos para antecipar cancelamentos e agir de forma preventiva.

---

## 🔗 Fonte dos Dados

Os dados utilizados estão disponíveis publicamente em:

📁 [`TelecomX_Data.json`](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json)

---

## 🛠 Tecnologias Utilizadas

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Análise Estatística
- Visualização de Dados

---

🚀 Projeto desenvolvido como parte dos desafios práticos da [Alura](https://www.alura.com.br/).
