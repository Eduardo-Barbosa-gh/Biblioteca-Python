
# Biblioteca Pandas 


## Apresentação da biblioteca:

---

Uma das bibliotecas mais utilizadas para analizar dados em Python.  
É um pacote de ferramentas que fornece estruturas de dados rápidas, flexíveis e expressivas, feito para tornar o trabalho com dados "relacionais" ou "rotulados" fácil e intuitivo.  
É uma ferramenta de análise/manipulação de dados de código aberto mais poderosa e flexível disponpivel em qualquer idioma.


## Características:

* Fácil manuseio de dados ausentes (Nan, NA ou NaT) em ponto flutuante (formato de representação digital de números racionais, que é usada nos computadores).
* Mutabilidade de tamanho (os objetos podem ser alinhados explicitamente a um conjunto de rótulos (alinha automaticamente os dados para você nos calculos).
* Agrupamento poderoso e flexível por funcionalidade para realizar operações split-apply-combine em conjuntos de dados, tanto para agregar quanto para transformar dados.



## Como instalar:
 As instruções de instalação completas estão disponíveis clicando [ aqui](https://pandas.pydata.org/pandas-docs/stable/install.html#dependencies).
 
  As principais depêndencias para a instalação desta biblioteca são às 3 seguintes:
  
- [ NumPy - Adiciona suporte para matrizes grandes e multidimensionais, matrizes e funções matemáticas de alto nível para operar nessas matrizes ](https://www.numpy.org)
- [ python-dateutil - Fornece extensões poderosas para o módulo datetime padrão ](https://dateutil.readthedocs.io/en/stable/index.html)
- [ pytz - Traz o banco de dados Olson tz para o Python, o que permite cálculos precisos e de fuso horário entre plataformas ](https://github.com/stub42/pytz)


## Exemplos de uso em bloco de código
### Maneira de importação:

---

import pandas as pd
pd.DataFrame({'A': [1, 2, 3]})

---

import pandas as pd

pd.DataFrame({'A': [1, 2, 3]})
Out[2]: 
   A
0  1
1  2
2  3

---
## Usabilidade:  
Uma das principais utilidades da Biblioteca é em Date Frame (semelhante a uma matriz mas as suas colunas têm nomes e podem conter dados de tipo diferente)

---

### 1º - Unique e Nunique
Função que retorna uma lista de elementos únicos com vvase na ocorrência. Inclui valores NaN.  
Particularmente útil para verificar os diferentes valores em um campo categórico.

Entrada:  
      data['Embarked'].unique()

Saída:  
      array (['S', 'C', 'Q', nan], dtype = objeto)

---

### 2º Describle
Mostra estatísticas descritivas, como média, desvio de padrão, máximo, mínimo e outras tendências centrais.

Entrada:  
data.describe()

Saída:
 ![Saída](https://insightlab.ufc.br/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2021/06/1.jpg.webp)


---
## Documentação 
Toda a documentação oficial está disponível em PyData.org: https://pandas.pydata.org/pandas-docs/stable

---

#### Fontes:
Guia de Pandas Dev - https://github.com/pandas-dev/pandas/blob/main/README.md  
Documentação de Pandas - https://pandas.pydata.org/pandas-docs/stable/index.html

