### A idéia de métricas de software está, ligada à gestão e controle de projetos. 
Lembre da velha máxima de Tom de Marco: “em algum lugar agora um projeto está falhando…” 
Alguém está pagando caro por não ter estimado e planejado corretamente um projeto de software.

Pontos por função é uma das técnicas (ou métodos) que proporcionam estimar a complexidade de um software. 
Formalmente, FPA é caracterizado como um método que busca medir a complexidade de um software pela quantificação das funcionalidades. 
É importante ressaltar que tal método foi criado em 1974 pela IBM e foi, posteriormente, desenvolvido por Caper Jones e pelo International Function Point Users Group.

Para inferir os pontos por função em um projeto de software necessário mapear:

• Os arquivos lógicos internos; a quantidade de campos em cada tabela e a quantidade de tuplas estruturadas para armazenar os registros.

• Os arquivos de interface externa.

• As entradas e a saídas de dados fornecidas pelo software.

Após mapear os valores quantitativos, destacados anteriormente, é necessário qualificá-los segundo a sua complexidade: baixa, média ou alta (essa planilha pode ajudar). 
Por fim, é necessário aplicar o fator de ajuste nos pontos mapeados, tal fator pode aumentar ou diminuir em 35% o número encontrado.
Definido o número de pontos por função ajustados é possível mapear o número de linhas de código por meio da tabela de conversão (veja uma experiência acadêmica realizada pelo autor deste texto).

Apesar da teoria de pontos por função ser datada de 1974, é possível perceber que a complexidade de um produto caracterizado como software toca os seguintes pontos: acesso e manipulação de arquivos internos e externos e elaboração de interface. Este fato determinou a estabilização do método, possibilitando assim, a sua aplicação durante todos esses anos.

Algumas empresas, aquelas que implementam os modelos qualitativos de software, aplicam (ou já aplicaram) pontos por função nas estimativas e, consequentemente, na gestão de seus projetos.

Não é trivial encontrar alguém que tope o desafio estampado no título deste texto. 
Vou mais além, acredito que a maioria das empresas não sabe o que representa um ponto por função dentro de seu escopo de produção. 
Lembre-se que a institucionalização da técnica de pontos por função ocorre junto com a estruturação de um processo de produção de software. 
A partir do momento que uma determinada empresa possui um conjunto de atividades bem definido, e nelas são gerados artefatos consistentes, é possível institucionalizar a técnica em questão. Destaco a necessidade de estabelecer uma base histórica de projetos, isto só acontece com o planejamento e controle de produção (pcp).
