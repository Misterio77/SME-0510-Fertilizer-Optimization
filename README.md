# Fertilizer Optimization

### Descrição do problema
O atual consumo brasileiro de fertilizantes é próximo a 45 milhões de toneladas por ano, o que nos torna o quarto maior consumidor, tendo à nossa frente apenas os Estados Unidos, a Índia e a China. A grande diferença entre o Brasil e os demais grandes consumidores, é que, aqui, 85% do consumo são importados, e esses outros países produzem a maior parte do que consomem. Entre os principais nutrientes necessários para a agricultura estão o nitrogênio, fósforo e potássio, elementos estes que são encontrados em produtos fertilizantes.
Entre as grandes empresas produtoras de fertilizantes, está a Yara, uma companhia que tem ganho notoriedade cada vez mais na maioria dos estados brasileiros. Fundada em 1905 para resolver a fome emergente na Europa, a empresa Yara tem uma presença mundial, tendo 24 unidades misturadoras de fertilizantes, na qual 4 estão localizadas no Brasil.
O Brasil desempenha um papel altamente estratégico nos negócios da Yara, sendo responsável por um terço do volume e um quarto do faturamento global da empresa. Isso significa interagir com mais de 25 mil produtores rurais. Nesse contexto, a companhia investe em soluções competitivas e sustentáveis para todos os tipos de culturas e solos encontrados aqui.
Com a finalidade de tornar possível encontrar a melhor logística de entregas de fertilizantes no Brasil, pretende-se minimizar o custo de entrega dos produtos em todos os estados brasileiros de tal forma que seja rentável para a empresa e satisfaça a demanda dos agricultores. As unidades de produção nacionais da empresa estão localizadas em:
- Ponta Grossa (Estado do Paraná);
- Paulínia (Estado de São Paulo);
- Cubatão (Estado de São Paulo);
- Rio Grande (Estado do Rio Grande do Sul);

Além disto, a corporação apresenta clientes em todas as capitais dos estados brasileiros, com suas respectivas demandas. Vale ressaltar que as demandas agrículas variam de estado para estado e os estados que possuem mais representatividade de produções agrícolas são: Mato Grosso, São Paulo, Minas Gerais, Rio Grande do Sul e Paraná. Conjuntamente, é necessário calcular o custo de entrega dos fertilizantes para cada estado do Brasil (considerando que a entrega saía de uma das unidades de produção nacionais). Este custo considera a distância entre uma unidade e a capital do estado em questão, somado à custos operacionais (combustível e manutenção de veículos). Por exemplo: Uma entrega de fertilizantes da 
`falar como é levado o fertilizante e o limite maximo do caminhao`

Integrantes
```

João Lucas Pereira e Sousa - 10994311
Joel Felipe Coelho - 4865826
Moniely Silva Barboza - 12563800
Ryan Souza Sá Teles - 12822062

```

## Modelagem do problema


## Variávias e Restrições

|              |  AC   |   AL    |   AP   |  AM   |    BA     |   CE   |   DF   |   ES    |    GO     |   MA    |    MT     |    MS     |    MG     |   PA    |   PB   |    PR     |   PE    |   PI    |   RJ   |   RN   |    RS     |   RO    |  RR   |   SC    |    SP     |   SE    |   TO    | Capacidade |
| :----------- | :---: | :-----: | :----: | :---: | :-------: | :----: | :----: | :-----: | :-------: | :-----: | :-------: | :-------: | :-------: | :-----: | :----: | :-------: | :-----: | :-----: | :----: | :----: | :-------: | :-----: | :---: | :-----: | :-------: | :-----: | :-----: | :--------: |
| Ponta Grossa |       |         |        |       |           |        |        |         |           |         |           |           |           |         |        |           |         |         |        |        |           |         |       |         |           |         |         |            |
| Paulínia     |       |         |        |       |           |        |        |         |           |         |           |           |           |         |        |           |         |         |        |        |           |         |       |         |           |         |         |            |
| Cubatão      |       |         |        |       |           |        |        |         |           |         |           |           |           |         |        |           |         |         |        |        |           |         |       |         |           |         |         |            |
| Rio Grande   |       |         |        |       |           |        |        |         |           |         |           |           |           |         |        |           |         |         |        |        |           |         |       |         |           |         |         |            |
| Demandas     | 3.191 | 147.765 | 15.405 | 9.209 | 1.833.484 | 18.902 | 64.408 | 432.794 | 3.172.005 | 651.672 | 1.768.070 | 1.768.070 | 4.002.179 | 460.812 | 62.776 | 4.102.398 | 147.598 | 431.327 | 52.802 | 41.707 | 4.243.212 | 130.364 | 9.331 | 845.988 | 4.272.363 | 112.214 | 618.331 |            |


## Como rodar o projeto
1. Baixe e instale [python](https://www.python.org/) em sua máquina
2. Instale as dependências: `pip install -r requirements.txt`
3. Rode o `main.py` e seja feliz

## Como testar o programa para outras variáveis
https://www.canalrural.com.br/noticias/agricultura/conheca-os-50-municipios-mais-ricos-na-agricultura-brasileira/
