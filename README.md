# Simulador de Crescimento Populacional

Projeto da disciplina **Modelagem e Simulação Matemática** – UniJorge.  
Nosso grupo desenvolveu um **software em Python com VPython** para simular o crescimento populacional utilizando **Progressão Aritmética (P.A.)** e **Progressão Geométrica (P.G.)**, com base em dados reais do **IBGE (Brasil, 2014–2024)**.

---

## 🎯 Objetivo
O objetivo deste trabalho é demonstrar, por meio de simulação, como populações crescem ao longo do tempo.  
O usuário poderá:
- Escolher a **população inicial**.
- Selecionar o **modelo de crescimento** (P.A. ou P.G.).
- Definir a **taxa de crescimento** (natalidade/mortalidade).
- Estabelecer o **número de anos** para simulação.
- Visualizar a evolução populacional em um **gráfico 3D animado**.

---

## 📊 Base de Dados (IBGE)
Utilizamos como referência os dados do **IBGE – Projeções Populacionais Revisão 2024**.

| Ano | População (aprox.) |
|-----|---------------------|
| 2014 | 202.765.190 |
| 2015 | 204.471.769 |
| 2016 | 206.114.067 |
| 2017 | 207.695.385 |
| 2018 | 209.225.090 |
| 2019 | 210.727.657 |
| 2020 | 212.152.243 |
| 2021 | 213.460.787 |
| 2022 | 214.699.434 |
| 2023 | 215.982.426 |
| 2024 | 217.166.648 |

Esses dados servem como **comparação** com os resultados gerados pelas fórmulas de P.A. e P.G.

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**  
- **VPython** (visualização e gráficos 3D)  
- **Pandas** (manipulação de dados)  
- **Matplotlib** (para comparações gráficas, se necessário)

---

## 👥 Divisão do Grupo
Cada integrante do grupo foi responsável por uma parte do código:

1. **Modelagem Matemática** – funções de P.A. e P.G.  
2. **Entrada de Dados** – inputs do usuário (população inicial, taxa, tempo).  
3. **Simulação** – loop da simulação populacional.  
4. **Gráfico 3D (VPython)** – plotagem dos resultados.  
5. **Animação (VPython)** – visualização da população crescendo.  
6. **Interatividade (VPython)** – sliders/botões para alterar parâmetros.  
7. **Integração e Testes** – unir todas as partes e corrigir erros.  

---

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/Simulador-Crescimento-Populacional.git
   cd Simulador-Crescimento-Populacional

2. Instale as dependências:

   pip install vpython pandas matplotlib

3. Execute o código principal:

python src/main.py

4. Siga as instruções no terminal ou na interface do VPython.

🏫 Contexto Acadêmico

Este trabalho será apresentado:

Na disciplina de Modelagem e Simulação Matemática (UniJorge).

Em uma escola pública parceira, como atividade de extensão.

📌 Contribuidores

[Nome 1] – Modelagem Matemática

[Nome 2] – Entrada de Dados

[Nome 3] – Simulação

[Nome 4] – Gráfico 3D

[Nome 5] – Animação

[Nome 6] – Interatividade

[Nome 7] – Integração e Testes
