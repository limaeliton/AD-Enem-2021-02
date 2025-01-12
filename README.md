# 📊 Análise Exploratória de Dados

Este projeto apresenta uma análise exploratória realizada em um conjunto de dados utilizando bibliotecas populares de Python, como **Pandas**, **Numpy**, **Matplotlib**, e **Seaborn**. O objetivo principal é fornecer insights acionáveis e visualizações que facilitam a tomada de decisões estratégicas.

---

## 🛠️ Ferramentas e Bibliotecas Utilizadas

- **Python 3.9+**
- **Pandas**: Manipulação e análise de dados.
- **Numpy**: Operações matemáticas e estatísticas.
- **Matplotlib** e **Seaborn**: Visualização de dados.

---

## 📂 Estrutura do Projeto

1. **Configuração do ambiente:** Configuração inicial, importação de bibliotecas e definição de parâmetros de exibição.
2. **Manipulação de Dados:**
   - Limpeza e normalização.
   - Criação de novas colunas e agregações.
3. **Visualizações e Insights:**
   - Gráficos exploratórios.
   - Análise de correlações e tendências.
4. **Conclusões e Recomendações.**

---

## 🔍 Principais Descobertas

### 1️⃣ Distribuição Geral dos Dados
Inserir uma imagem com gráfico representando a distribuição geral, como histograma ou gráfico de barras.
**Exemplo:**
```python
import matplotlib.pyplot as plt
import seaborn as sns

plt.figure(figsize=(10, 6))
sns.histplot(data=df, x="Coluna_Interesse", kde=True, color="#49deac")
plt.title("Distribuição da Coluna de Interesse")
plt.show()
