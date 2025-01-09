# Central Park Squirrel Census 🐿️

O objetivo deste repositório é realizar uma análise exploratória dos dados sobre o censo de esquilos do Central Park no ano de 2018, especificamente no mês de outrubro.

O Squirrel Census é um projeto multimídia de ciência, design e storytelling. Eles contam esquilos e apresentam suas descobertas ao público. A tabela utilizada no meu trabalho, contém dados de esquilos para cada um dos 3.023 avistamentos, incluindo coordenadas de localização, idade, cor primária e secundária da pelagem, elevação, atividades, comunicações e interações com humanos e entre eles mesmos.

O dataset pode ser encontrado no link a seguir: https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw/about_data

-----------------------
![mapa](mapa.jpeg)
_Esquilos no mapa de Central Parque._

## Objetivos:

- Limpeza de strings: Isolar colunas que serão desnecessárias para o projeto.

- Lidando com valores ausentes: Detectar presença de valores nulos ou constantes.

- Variáveis booleanas: Muitas colunas são booleanas.

- Distribuição de cores de pelagem: Visualizar a frequência de cada cor de pelagem primária e secundária. Identificar as cores mais comuns.

- Idade dos esquilos: Analisar a distribuição de idade.  Há uma diferença significativa entre a proporção de esquilos adultos e jovens?

- Atividades dos esquilos: Analisar a frequência de diferentes atividades (Running, Chasing, Climbing, etc.). Há correlações entre as atividades? Quais atividades são mais comuns em esquilos adultos versus jovens?

- Correlações entre variáveis: Explorar possíveis correlações entre variáveis usando matrizes de correlação.

- Localização: Uso de coordenadas para criar um mapa da localização dos esquilos. Existem áreas mais densamente povoadas por esquilos? Há relação entre a localização e a cor da pelagem ou atividade?


## Considerações finais:

- **Distribuição de Cores de Pelagem:** A cor de pelagem `Gray` é predominante entre os esquilos, seguida por `Gray` com `Cinnamon` e `Gray` com `White`. As demais cores aparecem com menor frequência.


- **Aparição dos Esquilos por Turno:** Há um aumento noturno na população de esquilos adultos, enquanto a maioria dos esquilos juvenis permanece no parque durante todo o dia.


- **Atividades dos Esquilos:** `Foraging` e `Eating` são as atividades mais comuns, evidenciando a busca por alimento como comportamento principal. `Running` e `Chasing` também são observados com frequência, sugerindo interações sociais e comportamentos de fuga.


- **Correlações entre Atividades:** Pode-se afirmar que existe uma correlação fraca entre `Climbing` e `Foraging` , ou seja, se um esquilo estiver fugindo, algumas das vezes ele escala em algum lugar.


- **Atividades por Idade:** Existe uma diferença significativa nas taxas de consumo entre adultos e juvenis, com maior frequência de `Eating` entre os juvenis.


- **Localização:** A distribuição geográfica das cores da pelagem dos esquilos apresenta um padrão simétrico, com agrupamentos de combinações de cores específicas em determinadas áreas.
