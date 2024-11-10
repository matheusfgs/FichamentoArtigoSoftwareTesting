# Software Testing of Generative AI Systems:Challenges and Opportunities

A. Aleti, "Software Testing of Generative AI Systems: Challenges and Opportunities," 2023 IEEE/ACM International Conference on Software Engineering: Future of Software Engineering (ICSE-FoSE), Melbourne, Australia, 2023, pp. 4-14, doi: 10.1109/ICSE-FoSE59343.2023.00009. 

# 1.Fichamento de Conteúdo:

O artigo aborda os desafios singulares para o **teste de software** apresentados por sistemas baseados em inteligência artificial generativa (GenAI), que são especialmente diferentes dos softwares tradicionais. O autor discute que os métodos convencionais de teste são muitas vezes insuficientes para abordar uma avaliação a esses sistemas, que produzem saídas criativas e variadas, complicando a definição de um “oráculo de teste” ou seja, uma referência altamente confiável para julgar a correção das respostas que são geradas. Em GenAI, o problema do oráculo ocorre porque as respostas não têm uma única “verdade” para comparação; elas são subjetivas e dependem do contexto, o que torna difícil determinar se uma saída é apropriada ou correta.O artigo analisa abordagens que podem ajudar a mitigar esses desafios, destacando dois tópicos principais: O aprendizado de oráculos específicos para GenAI e as medidas de adequação de conjuntos de teste para cobrir a diversidade de cenários e detectar possíveis vieses nas saídas geradas. É sugerido que um conjunto de testes adequado deve abranger uma ampla gama de cenários e ser sensível a vieses, permitindo identificar situações em que o sistema gera respostas inapropriadas. São discutidas técnicas como **testes metamórficos** e testes diferenciais. Destacando-se que estas técnicas apresentam limitações, já que muitas vezes as relações metamórficas não se aplicam a todos os tipos de entrada, e os testes diferenciais não cobrem adequadamente a diversidade das saídas possíveis. Também são abordadas técnicas como uso de benchmarks estáticos que por sua vez são consideradas limitadas e por conter risco de contaminação de dados. E para melhorar a avaliação da adequação dos testes em GenAI, o autor propõe o uso das **métricas de Test suite Instance Space Adequacy (TISA)** visando medir a qualidade de um conjunto de testes em termos de diversidade e cobertura, representando os casos de teste em um espaço bidimensional facilitando a identificação de lacunas na cobertura de testes e a falta de diversidade. Ao final o autor conclui que, à medida que sistemas GenAI avançam para áreas críticas, é essencial que sejam desenvolvidos novos métodos de teste que considerem a natureza criativa e também à imprevisibilidade dessas tecnologias.

# 2.Fichamento de Bibliográfico:


**.GenAI (Inteligência Artificial Generativa):** Subconjunto da inteligência artificial que se concentra em criar novos conteúdos, como textos, imagens ou músicas, em vez de apenas classificar ou interpretar dados existentes. Utiliza modelos complexos baseados em redes neurais para gerar informações a partir de padrões aprendidos nos dados de treinamento. (Página 1)

**.LLMs (Large Language Models)**
Modelos de linguagem extensivos treinados em grandes volumes de dados textuais para aprender a prever e gerar linguagem humana.
 Baseados em arquiteturas de transformadores, esses modelos, como GPT (Generative Pretrained Transformer) e BERT (Bidirectional Encoder Representations from Transformers), são capazes de entender e produzir textos em diversos contextos. (Página 2)

**.Wikidata:** Base de dados de conhecimento colaborativa e gratuita que estrutura informações em forma de dados e é mantida pela comunidade. (Página 4)

**.Instance Space (Espaço de Instâncias)**: Representação gráfica ou dimensional de todos os cenários ou casos de teste possíveis que um sistema pode encontrar. Utilizado para analisar a diversidade e cobertura de testes, garantindo que o conjunto de testes explore várias condições e características de entradas. (Página 4)

**.Test suite Instance Space Adequacy (TISA)**: Métrica que mede a qualidade e adequação de um conjunto de testes com base na diversidade e cobertura das instâncias de teste. (Página 9)

# 3.Fichamento de Citações:


“GenAI, while being a relatively new technology, it has already see a myriad of applications. For example, at the start of the pandemic, Allen AI compiled the CORD-19 dataset [91] with the objective of aiding public health experts in effectively navigating the extensive array of COVID-19 research papers that rapidly emerged. Following this, NLPservices like Amazon Kendra were employed to streamline the organization of research insights related to COVID-19” (Página 6, III - GENAI SYSTEMS)

"Automated testing of AI systems has been significantly researched, with an exponential increase in the number of papers in the last few years” (Página 6, IV - AUTOMATED TESTING OF GENAI SYSTEM)

“As GenAI systems continue to permeate various domains,from creative content generation to complex decision-making,ensuring their quality and correctness is of paramount importance” (Página 9, VII - Conclusão


