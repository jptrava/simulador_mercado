# Simulador de Caixas de Supermercado

Este repositório está destinado a armazenar o código que se resolve a atividade proposta.

## 1) Execute a simulação para µ = 5,0, σ = 0,5, N = 100 clientes e 1000 rodadas. Registre a média e o desvio-padrão obtidos.

Com Número de caixas = 1

Média de tempo para atendimento do cliente = 252,499 minutos
Desvio padrão de tempo para atendimento do cliente = 2,9 minutos

Com Número de caixas = 100 (Para igualar o número de clientes)
Média de tempo para atendimento do cliente = 5 minutos
Desvio padrão de tempo para atendimento do cliente = 0,49 minutos

## 2) Varie o número de caixas de 1 para 2 e 3. Compare os resultados obtidos e discuta qualitativamente como mais caixas podem reduzir o tempo médio de atendimento.

Com Número de caixas = 1

Média de tempo para atendimento do cliente = 252,499 minutos
Desvio padrão de tempo para atendimento do cliente = 2,9 minutos

Com Número de caixas = 2

Média de tempo para atendimento do cliente = 127,498 minutos
Desvio padrão de tempo para atendimento do cliente = 1,46 minutos

Com Número de caixas = 3

Média de tempo para atendimento do cliente = 85,854 minutos
Desvio padrão de tempo para atendimento do cliente = 0,974 minutos

O número de caixas impacta diretamente o tempo que o cliente espera na fila. É importante ressaltar que o tempo médio de atendimento individual (µ) não muda, mas sim o tempo médio que cada cliente passa 
no sistema, pois ao seu atendimento somam-se os tempos de atendimento dos clientes posteriores. A partir disso, é possível calcular a média de tempo gasto por cliente. A quantidade de caixas funciona 
como um paralelismo no processo, já que divide a fila em partes; assim, com filas menores, o tempo médio que cada cliente passa na fila também diminui.

## 3) Varie σ (ex.: 0,25, 1,0, 2,0) e observe como a variabilidade impacta os resultados médios.




## 4) Escreva um parágrafo explicando por que este simulador é considerado estocástico e como isso representa situações reais.

O simulador pode ser considerado estocástico, pois suas saídas sempre variam de acordo com dados definidos de maneira aleatória (ou pseudoaleatória, neste caso), mesmo quando são aplicados valores 
de média e desvio-padrão. Ele reflete situações reais, já que o atendimento em um mercado não é totalmente previsível, sendo impossível calcular de maneira exata apenas com valores fixos de entrada. 
A aleatoriedade imposta no código serve para representar os diversos fatores que podem gerar variações no tempo médio de atendimento na vida real.
