# 🏋️ Análise de Dados de Treinos de Membros de uma Academia

Este repositório contém a análise de dados de uma planilha detalhada sobre os treinos de membros de uma academia. O objetivo é extrair *insights* valiosos, identificar padrões de desempenho e saúde, e gerar visualizações que  nos ajude a entender mais sobre os padrões que essa planilha nos dá.

---

## 🎯 **Objetivos da Análise**

* **Relacionar dados biométricos com o desempenho:** Analisar como a idade, gênero, peso e BMI se correlacionam com métricas como calorias queimadas e duração da sessão.
* **Avaliar a eficácia dos treinos:** Comparar a média de calorias queimadas e BPMs (Batimentos por Minuto) para diferentes tipos de treino (`Workout_Type`).
* **Analisar a frequência de treino e seus efeitos:** Investigar como a frequência semanal e o nível de experiência (`Experience_Level`) influenciam nos resultados, como a porcentagem de gordura corporal.
* **Criar visualizações:** Gerar gráficos e *dashboards* que ajudem a entender os dados mais profundamente.

---

## 📊 **Dados Utilizados**

A análise foi realizada a partir de uma planilha retirada do Kaggle (https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset) que contém as seguintes colunas, divididas por categorias para facilitar a compreensão:

#### **Dados Biométricos**
* `Age`: Idade do membro.
* `Gender`: Gênero do membro.
* `Weight (kg)`: Peso em quilogramas.
* `Height (m)`: Altura em metros.
* `BMI`: Índice de Massa Corporal (Body Mass Index).
* `Fat_Percentage`: Porcentagem de gordura corporal.

#### **Métricas de Treino**
* `Workout_Type`: Tipo de treino realizado (Cardio, Musculação, HIIT e Yoga).
* `Session_Duration (hours)`: Duração da sessão de treino em horas.
* `Calories_Burned`: Calorias queimadas durante o treino.
* `Water_Intake (liters)`: Consumo de água em litros.

#### **Métricas de Saúde e Desempenho**
* `Max_BPM`: Batimentos por minuto máximos alcançados.
* `Avg_BPM`: Batimentos por minuto médios durante o treino.
* `Resting_BPM`: Batimentos por minuto em repouso.
* `Workout_Frequency (days/week)`: Frequência semanal de treinos.
* `Experience_Level`: Nível de experiência do membro (Iniciante = 1; Intermediário = 2; Avançado = 3).

---

## 🛠️ **Ferramentas e Tecnologias**

* **Python**: Linguagem principal para a análise.
* **Pandas**: Biblioteca para manipulação e limpeza dos dados.
* **Matplotlib/Seaborn**: Bibliotecas para visualização de dados.
* **PowerBI**: Para gerar visualizações para entender mais sobre os dados e gerar gráficos com insights.

---

## 📂 **Estrutura do Repositório**

* `data/`: Pasta contendo a planilha de dados brutos ('gym_members_exercise_tracking.csv') e a planilha com os dados limpos ('Dados_de_exercicio_limpo.csv')
* `Python`: Pasta para armazenar o código Python utilizado para limpar os dados e realizar uma primeira análise exploratória.
* `relatorios/`: Pasta para armazenar relatórios ou imagens dos gráficos.
* `README.md`: Este arquivo.

---

## 📝 **Resultados e Conclusões**

