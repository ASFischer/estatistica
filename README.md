o Caos aos Dados: O Poder da Amostragem e Estatística com Python 📊🐍

Recentemente, aprofundei meus estudos em fundamentos essenciais da Ciência de Dados, e a principal lição é: antes de treinar qualquer modelo, você precisa entender a "alma" dos seus dados.

Dividi esse aprendizado em três pilares práticos:

1. Estratégias de Amostragem (Garantindo a Justiça)

Não basta apenas "pegar um pedaço" dos dados. Utilizei bibliotecas como NumPy e Scikit-Learn para aplicar diferentes técnicas:

Simples: Seleção aleatória pura.

Sistemática: Escolha de um ponto inicial e saltos de $k$ em $k$ (ideal para grandes volumes).

Estratificada: Essencial para manter a proporção das classes (como as espécies no dataset Iris), garantindo que grupos menores não sejam ignorados.

2. Medidas de Centralidade e Dispersão

Para descrever um conjunto de dados, olhei além da média. Entender a mediana, moda, desvio padrão e quartis é o que permite identificar outliers e a variabilidade real, algo fundamental para diagnósticos precisos.

3. O Teste da Normalidade

Nem tudo na vida é uma "curva de sino". Usei o scipy.stats para realizar testes de normalidade e criar gráficos Q-Q Plots (probplot). Saber se seus dados seguem uma distribuição normal é o divisor de águas para escolher o algoritmo de Machine Learning correto.

A jornada para se tornar um bom analista não é apenas sobre rodar código, mas sobre saber o porquê de cada escolha estatística.


