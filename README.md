<h2>PROBLEM STATEMENT: Em busca do craque!</h2>
---
<p>A Copa do Mundo da FIFA Catar 2022 está cada vez mais próxima e o técnico da seleção brasileira de futebol, Adenor Leonardo Bachi, mais conhecido como Tite, vem andando cada vez mais estressado e pressionado, pois ainda precisa recrutar um jogador para ocupar a posição de ponta-direita do time.</p>
<p>Tite está indeciso entre três atletas e, para fazer a escolha, resolveu fazer a análise do número de bolas colocadas na grande área por cada jogador em suas últimas partidas. Em caso de empate, o novo critério usado será o de aproveitamento, calculando a taxa de finalizações (chutes a gol) convertidas em gols, através da fórmula: (gols/finalizações) * 100.</p>
<p>Para elaborar esse complexo algoritmo, Tite resolveu contatar o Centro de Informática da UFPE e VOCÊ foi o programador escolhido para auxiliá-lo nessa tarefa!</p>
<p>Obs: não será permitido o uso das funções max(), min() ou qualquer outra semelhante.</p>
<h3>Input</h3>
---
<p>Você receberá 12 entradas, 4 para cada jogador, contendo os nomes dos jogadores, a quantidade de bolas colocadas na grande área por cada um, bem como o número de chutes a gol e o número de gols marcados, a fim de calcular suas respectivas taxas de aproveitamento.</p>
- Nome do jogador (string) 
<br/>
- Bolas colocadas na grande área (inteiro)
<br/>
- Finalizações (inteiro)
<br/>
- Gols (inteiro)
<h3>Output</h3>
---
<p>Inicialmente, caso os jogadores com maior número de bolas colocadas na grande área estejam empatados, você deverá imprimir:</p>
-> Tite está mais indeciso do que nunca!
<br/><br/>
<p>Em seguida, você deverá imprimir três linhas contendo os nomes de todos os jogadores em ordem do melhor para o pior, de acordo com os critérios discutidos anteriormente. Após isso, você deverá imprimir:</p>
-> Finalmente o técnico da seleção brasileira liberou a escalação completa do time! O ponta-direita escolhido foi…
<br/><br/>
<p>Por fim, caso o número de bolas colocadas na grande área do jogador escolhido for menor ou igual a 10, imprima:</p>
-> {melhor_jogador}?! Sei não hein Galvão…
<br/><br/>
<p>Caso contrário, imprima:</p>
-> {melhor_jogador}! Dessa vez o hexa vem pra casa!!