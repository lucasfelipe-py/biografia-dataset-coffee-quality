BIOGRAFIA DATASET

---

### Contexto
O dataset possui informações detalhadas sobre a avaliação da qualidade de diferentes tipos de café, incluindo aspectos como aroma, sabor, corpo, equilíbrio, e outros. Ele provavelmente foi criado para oferecer insights sobre as características que contribuem para a qualidade do café em benefício de produtores, consumidores e interessados em entender e melhorar a qualidade do café.

### Formato do dataset
CSV

### Dados Faltantes
Há campos com valores ausentes, como o ano da colheita para algumas entradas e o método de processamento para outras. Isso pode requerer atenção na limpeza dos dados antes de qualquer análise posterior.

### Estrutura do Dataset
- **ID**: Um identificador único para cada registro.
- **Espécie**: A espécie do café (como Arábica).
- **Continente de Origem**: O continente onde o café foi cultivado.
- **País de Origem**: O país específico de origem do café.
- **Ano da Colheita**: O ano em que o café foi colhido.
- **Validade**: A data de validade do café.
- **Variedade**: A variedade do café.
- **Cor**: A cor dos grãos de café.
- **Método de Processamento**: Como o café foi processado.
- **Quakers (tipo de defeito)**: Booleano

### Notas de 0 a 10
- Aroma
- Sabor
- Corpo
- Equilíbrio
- Uniformidade
- Xícara Limpa
- Doçura
- Umidade

### Acesso e Licença
- **Acesso**: O dataset está disponível em plataformas como Kaggle e GitHub.
- **Licença**: [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)

### Disponibilidade
- [Kaggle Dataset](https://www.kaggle.com/datasets/adampq/coffee-quality-with-locations-of-origin)

### Fontes
- [Kaggle Dataset por FatihB](https://www.kaggle.com/datasets/fatihb/coffee-quality-data-cqi)
- [Kaggle Dataset por Volpatto](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi)
- [GitHub Repository por Fatih Boyar](https://github.com/fatih-boyar/coffee-quality-data-CQI/tree/main)
- [Coffee Institute](https://www.coffeeinstitute.org/)

### Métodos de extração dos dados
Scripts de web scrapping com Python para coletar dados do site [Coffee Institute Database](https://database.coffeeinstitute.org/). 
Os códigos de extração foram disponibilizados no [repositório do GitHub](https://github.com/jldbc/coffee-quality-database).

---