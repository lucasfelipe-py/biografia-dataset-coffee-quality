## Biografia do Dataset
- **Link:** <br>[Dataset](Coffee_Qlty.csv)

- **Descrição:** <br>O dataset possui informações detalhadas sobre a avaliação da qualidade de diferentes tipos de café, incluindo aspectos como aroma, sabor, corpo, equilíbrio, e outros. Ele provavelmente foi criado para oferecer insights sobre as características que contribuem para a qualidade do café em benefício de produtores, consumidores e interessados em entender e melhorar a qualidade do café.

- **Formato do dataset:** <br>CSV

- **Dados Faltantes:** <br>Há campos com valores ausentes, como o ano da colheita para algumas entradas e o método de processamento para outras. Isso pode requerer atenção na limpeza dos dados antes de qualquer análise posterior.

## Estrutura do Dataset
- **ID**: Um identificador único para cada registro
- **Espécie**: A espécie do café (como Arábica)
- **Continente de Origem**: O continente onde o café foi cultivado
- **País de Origem**: O país específico de origem do café
- **Ano da Colheita**: O ano em que o café foi colhido
- **Validade**: A data de validade do café
- **Variedade**: A variedade do café
- **Cor**: A cor dos grãos de café
- **Método de Processamento**: Como o café foi processado
- **Quakers (tipo de defeito)**: 0 para "não possui", 1 para "possui"
- Aroma: Nota de 0 a 10
- Sabor: Nota de 0 a 10
- Corpo: Nota de 0 a 10
- Equilíbrio: Nota de 0 a 10
- Uniformidade: Nota de 0 a 10
- Xícara Limpa: Nota de 0 a 10
- Doçura: Nota de 0 a 10
- Umidade: Nota de 0 a 10

## Disponibilidade
[Kaggle Dataset](https://www.kaggle.com/datasets/adampq/coffee-quality-with-locations-of-origin)<br>
[Kaggle Dataset por FatihB](https://www.kaggle.com/datasets/fatihb/coffee-quality-data-cqi)<br>
[Kaggle Dataset por Volpatto](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi)<br>
[GitHub Repository por Fatih Boyar](https://github.com/fatih-boyar/coffee-quality-data-CQI/tree/main)<br>
[Coffee Institute](https://www.coffeeinstitute.org/)<br>

**Licença**: [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)

## Métodos de extração dos dados
- Scripts de web scrapping com Python para coletar dados do site [Coffee Institute Database](https://database.coffeeinstitute.org/)
- Os códigos de extração foram disponibilizados no [repositório do GitHub](https://github.com/jldbc/coffee-quality-database)
