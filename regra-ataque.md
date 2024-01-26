# Regra do Ataque do jogo CombatsForce

A regra do ataque do jogo CombatsForce, será realizada em etapas descritas a baixo:

### 1 - Confronto aéreo
A primeira etapa do ataque é o confronto aereo, isso é será confrontando o ataque das **bombas vs os mísseis** da defesa.
Nessa etapa o confronto é simples, 1 para 1.
Será verificado a quantidade de bombas enviadas no ataque contra a quantidade de misseis no batalhao da defesa. E nesse confronto será subtraido a quantidade de bombas do ataque pela quantidade de misseis da defesa.

Exemplo:
 - Ataque com **10 bombas**
 - Defesa com **8 misseis**

> Neste exemplo irão ser destruídas 8 bombas no ar e os 8 misseis da defesa. Irá sobrar ainda 2 bombas do ataque que irão cair no alvo escolhido no momento do ataque.

### 2  - Ataque a edifícios pelas bombas
Após o confronto aereo, as bombas restantes seguem rumo ao alvo definido no momento do ataque.
> Quando enviado um ataque com bombas, neste momento o atacante deverá escolher um edificio do batalhão alvo para ser atacado pelas bombas.

Ao chegar no batalhão destino, deverá ser buscado dentro do batalhão o edifício alvo. Se for encontrado as bombas irão danificar o edificio, baixando os seus pontos de vida. 
Quando os pontos de vida do batalhão for igual ou menor que zero, um nivel do batalhão será descontado e a quantidade de vida do nivel inferior do edificio será reestabelecido.

Quando o nivel do edificio chegar a zero o mesmo eh destruido.

Ainda nessa fase um ataque com com tanques irão nessa etapa danificar as torres, podendo baixar os seus bonus na defesa.

### 3 - Confronto das tropas
-----???

### 4- Espionagem
Após o confronto das tropas, será verificado as unidades restantes no ataque e defesa. Se foi feito um ataque junto com espiões e eles sobreviveram no confronto das tropas, então será verificado o nivel de espionagem. Para determinal o nivel de espionagem serão avalidados os espiões que retornarão a base.
Segundo a tabela a baixo:

| Nível | Revelar                             | Condição               |
|:-----:|:------------------------------------|:-----------------------|
| 1     | Quantidade de unidades              | \>= 1 espião retornou  |
| 2     | Quantidade de recursos do defensor  | \>= 50% retornaram     |
| 3     | Lista de edifícios e seus níveis    | \>= 70% retornaram     |
| 4     | Unidades fora do batalhão           | \>= 90% retornaram     |

### 5 - Ação dos diplomatas
Nesta fase será verificado se o ataque foi realizado junto com `diplomatas`, neste caso e sobrevivendo depois do confronto das tropas, o batalhão sob ataque irá sofrer perda de vida do seu batalhão entre um intervalo de minimo e maximo configurado no mundo em questão + 5 pontos de vida para cada diplomata que sobfreviveu, respeitando a perda máxima configurada.

Quando a vida do batalhão chegar a zero o mesmo será conquistado, passado o controle do batalhão atacado para o atacante. E a tropa restante ficará no batalhão para dar apoio.

### 6 - Saquear os recursos
Nesta etapa, se na etapa dos diplomatas o batalhão não foi conquistado, será avaliado a `capacidade de carga` da tropa que irá retornar a base e saquear proprorcionalmente os recursos do batalhão atacado. E esses recursos saquedos irão retornar junto com a tropa e creditados quando a tropa retornar a base.

### 7 - Retornar a base
Não sendo conquistado o batalhão, a tropa restante irão voltar a base e irão levar o tempo necessário conforme a velocidade da tropa restante.
