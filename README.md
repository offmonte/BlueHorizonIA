# BlueHorizon GlobalSolution 2024

## Contexto

As maiores cidades litorâneas são geralmente cidades portuárias. Devido aos portos, o mar ao redor dessas cidades é frequentemente muito poluído. Usando Santos como exemplo, até 4,5 km nas proximidades do porto, a água não é boa o suficiente para sustentar vida marinha.

## Solução

Nossa solução consiste em uma inteligência artificial que analisa dados de qualidade da água (pH, oxigenação, microplásticos e nutrientes) e determina se a água está melhorando para suportar vida. Para incentivar melhorias, os portos pagarão menos impostos conforme a qualidade da água melhora, medida por sensores específicos.

Para conscientizar a população sobre as mudanças feitas e como a melhora da qualidade da água e o incentivo fiscal estão afetando suas vidas, será desenvolvido um aplicativo.

## Consequências

As consequências desta iniciativa podem incluir melhores preços ao consumidor final devido à redução de impostos na importação e incentivo ao turismo sustentável local, uma vez que a fauna marinha recuperada atrairá visitantes de várias partes.

## Sobre o Dataset

Um dataset que avalie a qualidade da água para a fauna marinha deve considerar variáveis que impactam significativamente a saúde e o bem-estar dos organismos marinhos. As cinco variáveis recomendadas são:

1. **pH**: O nível de acidez ou alcalinidade da água. O pH ideal para a maioria dos organismos marinhos está entre 7.5 e 8.4.
2. **Oxigenação da Água (Oxigênio Dissolvido)**: A quantidade de oxigênio disponível na água. Níveis adequados são essenciais para a respiração dos organismos aquáticos. Valores acima de 5 mg/L são geralmente considerados bons.
3. **Nutrientes (Nitrogênio e Fósforo)**: A presença de nutrientes como nitrato (NO3-) e fosfato (PO4³-) na água. Concentrações excessivas podem causar eutrofização, levando à proliferação de algas e condições hipóxicas.
4. **Presença de Microplásticos**: Pequenos fragmentos de plástico que podem ser ingeridos por organismos marinhos, causando danos físicos e químicos.
5. **Salinidade**: A concentração de sal na água. A salinidade afeta a osmose e o equilíbrio hídrico dos organismos marinhos. A salinidade típica da água do mar é de cerca de 35 ppt (partes por mil).

## Porque Usamos o kNN?

O kNN (k-Nearest Neighbors) é um algoritmo de aprendizado supervisionado usado principalmente para classificação e regressão. Ele classifica um ponto de dados com base na classe predominante dos k pontos de dados mais próximos a ele no espaço de características.

## Conclusão

O modelo foi bem treinado com kNN devido aos pontos de características próximas. Entretanto, é necessário realizar testes com dados reais, pois os dados de mock podem estar enviesados.
