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
xxx

### 4- Espionagem
Após o confronto das tropas, será verificado as unidades restantes no ataque e defesa. Se foi feito um ataque junto com espiões e eles sobreviveram no confronto das tropas, então será feito o confronto dos espiões, aqui também 1 para 1. Quantidade de espiões do ataque contra a quantidade de espiões na defesa. Nesse confrotno os espiões não morrem mais, só verificado a quantidade de espiões do ataque que serão eficientes na espionagem. o resultado dos espiões do ataque após esse confronto será o nível de espionagem que o ataque terá.
Segundo a tabela a baixo:

1. <= 5 espiões  = recursos totais da defesa
2. > 5 e <= 15 = quantidade de unidades na defesa (- diplomatas)
3. > 15 e <= 20 = lista de edifícios e niveis
4. > 20 = lista de diplomatas

### 5 - Ação dos diplomatas
xxxx

### 6 - Saquear os recursos
xxx

### 7 - retornar a base
xxx