# 🧬 Introdução à Programação Python para Biocientistas

Bem-vindos ao repositório da disciplina de introdução à programação em Python, voltada para a pós-graduação em Ciências Farmacêuticas (FCF/UNESP). 

Este material foi desenvolvido para demonstrar como a programação pode ser uma ferramenta indispensável no dia a dia do biocientista, facilitando análises de dados, automação de tarefas e modelagem de bioprocessos.

## 📚 Conteúdo da Aula 01

Neste primeiro módulo, focamos na ambientação e nos conceitos básicos da linguagem, sempre com aplicações voltadas para a biotecnologia:

* **O Ecossistema Python na Ciência:** Mostra a potencialidade das bibliotecas como Biopython, Pandas e NumPy.
* **O Ambiente Google Colab:** Como utilizar a ferramenta como um verdadeiro Caderno de Laboratório Eletrônico (inserção de textos em Markdown, equações em LaTeX e imagens).
* **Fundamentos da Linguagem:**
  * Operações matemáticas básicas e variáveis.
  * Operadores lógicos (aplicados ao controle de parâmetros em biorreatores).
  * Manipulação de Strings e *slicing*.
  * Formatação moderna de textos (f-strings) para relatórios experimentais.
* **Exercícios Práticos:**

## 📚 Conteúdo da Aula 02

* **Aplicação Prática:** Calculadora de Índice de Massa Corporal (IMC) com classificação automática do indivíduo (Abaixo do peso, normal, sobrepeso, etc).

**Laços de Repetição (*Loops*)**
* Uso da estrutura `while` para repetições baseadas em condições (ex: contagem regressiva de um foguete).
* Uso da estrutura `for` com a função `range()` para iterar sobre listas de dados.
* Conceitos fundamentais de **contadores** e **acumuladores** (ex: cálculo do fatorial de um número).
* Como interromper repetições infinitas ou baseadas em gatilhos utilizando o comando `break`.

### Desafio Prático: Simulador de Crescimento Microbiano
No fim do notebook, consolidamos o aprendizado com um desafio aplicado à Engenharia de Bioprocessos. O aluno deve interagir com um algoritmo que estima o crescimento exponencial de uma cultura celular, calculando quantas gerações são necessárias para que um inóculo inicial atinja uma população alvo específica.

## 📚 Conteúdo da Aula 03 -Funções, NumPy e Matplotlib para Biocientistas

Nesta terceira aula, avançamos para a automação de cálculos e a visualização de dados científicos, saindo do Python básico e entrando no ecossistema de bibliotecas essenciais para a engenharia e as ciências biológicas.

### 📌 Tópicos Abordados

*   **Funções (Automatizando Cálculos Repetitivos):**
    *   Conceito de encapsulamento: como criar "máquinas" que recebem parâmetros, processam dados e retornam resultados (`return`).
    *   Aplicações práticas: funções genéricas para cálculos de dimensionamento (volumes de reatores cilíndricos) e propriedades geométricas complexas (análise de esferas).
    *   Uso de *docstrings* para documentação de código e formatação avançada de *strings* (ex: exibição correta de expoentes e símbolos como $m^2$ e $\pm$).

*   **Introdução ao NumPy (O Motor Numérico):**
    *   O conceito de bibliotecas e a limitação das listas nativas do Python para matemática.
    *   `np.array()`: Transformação de dados brutos (ex: triplicatas de laboratório) em vetores matemáticos de alto desempenho.
    *   **Geração de Dados:** Uso de `np.linspace()` para criar eixos contínuos para modelos teóricos e `np.arange()` para simular cronogramas de amostragem por passos.
    *   **Estatística de Bancada:** Tratamento rápido de dados experimentais utilizando `np.mean()` (média) e `np.std()` (desvio padrão).

*   **Visualização de Dados com Matplotlib:**
    *   **Gráficos 2D Clássicos (`plot`):** Construção passo a passo de cinéticas de crescimento celular (tempo vs. densidade óptica), adicionando rótulos, títulos e grades.
    *   **Abordagem Orientada a Objetos (`fig, ax`):** O padrão ouro para plotar múltiplas curvas no mesmo eixo e criar gráficos com qualidade de artigo científico.
    *   **Histogramas (`hist`):** Análise estatística e distribuição de frequências, com exemplo prático modelando a curva de distribuição normal (Gaussiana) da estatura populacional.
    *   **Gráficos 3D (`plot_surface`):** Criação de superfícies tridimensionais complexas utilizando `np.meshgrid`, simulando, por exemplo, o efeito combinado da Temperatura e do pH na atividade enzimática.


## 🚀 Como acessar e executar as aulas

Não é necessário instalar nenhum software no seu computador para acompanhar esta disciplina. Utilizaremos o **Google Colaboratory**, que roda o código Python diretamente na nuvem pelo seu navegador.

Para abrir a Aula 01 e executar os códigos, basta clicar no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](Capítulo_01_Introdução_ao_Python.ipynb)

Para abrir a Aula 02 e executar os códigos, basta clicar no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](Aula_02_Python_Introdução.ipynb)

Para abrir a Aula 03 e executar os códigos, basta clicar no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](Aula_03_Introdução_ao_Python_para_biocientistas.ipynb)


> **Nota para os alunos:** Após abrir o arquivo no Colab, lembre-se de clicar em `Arquivo > Salvar uma cópia no Drive` para que você possa fazer suas próprias anotações e resolver os exercícios propostos sem perder o seu progresso.

## 🛠️ Pré-requisitos

* Uma conta Google (Gmail ou e-mail institucional associado ao Google).
* Acesso à internet e um navegador atualizado.
* Curiosidade e vontade de aprender a integrar ciência de dados à pesquisa biológica!

---
**Professor Responsável:** Marcel Otavio Cerri  
**Departamento:** Engenharia de Bioprocessos e Biotecnologia  
**Instituição:** UNESP - Universidade Estadual Paulista (Campus Araraquara)
**Contato:** marcel.cerri@unesp.br
