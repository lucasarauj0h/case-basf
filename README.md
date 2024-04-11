# case-basf

Acesso ao código via Google Colab - [Click Here](https://colab.research.google.com/drive/1c11rfWPBD9soM3bsPRXShq6atF9fd9Cs?usp=sharing)

## Relatório

OBS: Antes de começar a esmiuçar a base de dados, foram feitos uma pré-análise dos dados utilizando o pivot table do Excel, e também a biblioteca ydata-profiling sendo assim, já iniciei a exploração via python com objetivos fixados. Também foram feitas outras análises via Python que foram removidas, por não demonstrarem nada relevante para a exploração.

<hr>

### **Exploratory Data Analysis (EDA)**

### Correlação entre Matérias-Primas e Preços:

- Não foi identificada uma relação direta entre o tipo de matéria-prima base, o tipo de grupo principal e os valores finais do produto. As médias e medianas são próximas, e o grande valor de desvio padrão sugere que não há uma correlação forte entre as variáveis analisadas e o preço final do produto.

### Correlação entre Matérias-Primas e Matéria-Prima Base do Produto: 

- Foi analisada a correlação entre o tipo de matéria-prima base, o grupo primário e a matéria-prima usada na composição do produto. Foi possível identificar os tipos de matéria-prima base e grupo primário mais presentes nos dados e compreender melhor como essas variáveis se relacionam com a matéria-prima usada na composição dos produtos. Observou-se uma correlação entre o valor final do produto e a quantidade total ou "concentração" de matéria-prima utilizada.

### Conclusão

- A análise realizada sugere que a quantidade total ou concentração de matéria-prima utilizada tem uma correlação com o valor final do produto, enquanto o tipo específico de matéria-prima base e grupo primário não parecem ter uma influência direta nos preços finais. Essas informações podem ser úteis para otimizar a produção e os custos dos produtos, focando na eficiência da utilização das matérias-primas disponíveis.
