Claro! Aqui está a explicação estruturada e profissional do seu novo projeto de **Regressão Linear Simples**, ideal para colocar no seu `README.md` no GitHub:

---

# 📈 Análise de Regressão Linear Simples — Relação entre Anos de Educação Superior e Salário

Este projeto tem como objetivo investigar se os **anos de educação superior** influenciam o **salário** dos colaboradores de uma empresa, utilizando uma amostra real de 46 funcionários. A partir disso, buscamos construir um **modelo preditivo** baseado em **regressão linear simples**.

## 🔧 Tecnologias e Bibliotecas Utilizadas

- **Pandas / NumPy**: Manipulação de dados  
- **Matplotlib / Seaborn**: Visualização gráfica  
- **Statsmodels**: Ajuste e avaliação de modelo de regressão  

---

## 📊 Pergunta de Negócio

> 🎯 O salário de um colaborador muda de acordo com os anos de educação superior?  
> 📐 Se sim, é possível estimar o salário com base nesses anos de estudo?

---

## 📥 Etapas do Projeto

### 1. **Importação e Preparação dos Dados**
- Leitura da base de dados `base_funcionarios_v1.csv` com índice sendo o campo `id`
- Visualização preliminar dos dados (`head`, `describe`)

### 2. **Análise Exploratória dos Dados**
- Criação de um **gráfico de dispersão** entre `Anos_Educ_Superior` e `Salario` para visualizar a relação entre as variáveis.
- Cálculo e visualização da **correlação de Pearson** com `heatmap` para medir o grau de associação linear entre as variáveis.

### 3. **Construção do Modelo de Regressão Linear**
- Definição da variável resposta (`Salario`) e da variável explicativa (`Anos_Educ_Superior`)
- Adição do termo de **intercepto** ao modelo
- Ajuste do modelo utilizando `statsmodels.OLS`
- Análise do resumo estatístico (`summary()`) que inclui:
  - Coeficientes
  - R² (coeficiente de determinação)
  - p-valores
  - Intervalos de confiança

### 4. **Visualização da Regressão**
- Utilização do `regplot` para exibir a linha de regressão ajustada sobre os dados.

---

## 📌 Interpretação Esperada

- Verificar se há uma **associação estatisticamente significativa** entre os anos de estudo e o salário
- Observar a **força dessa relação** (via R²)
- Utilizar o modelo ajustado para **prever salários** futuros com base nos anos de educação superior

---

## ✅ Conclusões e Possíveis Extensões

- A análise permite entender se a **formação acadêmica tem impacto direto na remuneração**.
- Pode ser expandido para um modelo de **regressão linear múltipla**, incluindo variáveis como tempo de empresa, cargo, setor, etc.
- Abre caminho para aplicar **técnicas mais avançadas de Machine Learning** no futuro.

