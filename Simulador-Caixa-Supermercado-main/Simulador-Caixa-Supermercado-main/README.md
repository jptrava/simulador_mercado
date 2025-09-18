#Simulador de Caixas de Supermercado#
Este repositório contém o código desenvolvido para a atividade proposta. Ele simula o fluxo de clientes e o tempo de espera em caixas de supermercado.

#1) Simulação para µ = 5,0, σ = 0,5, N = 100 clientes e 1000 rodadas.#
Com 1 caixa

Tempo médio de atendimento do cliente: 252,499 minutos

Desvio padrão do tempo de atendimento: 2,9 minutos

Com 100 caixas (equivalente ao número de clientes)

Tempo médio de atendimento do cliente: 5 minutos

Desvio padrão do tempo de atendimento: 0,49 minutos
_______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
#2) Variação do número de caixas de 1 para 2 e 3.#
Com 1 caixa

Tempo médio de atendimento do cliente: 252,499 minutos

Desvio padrão do tempo de atendimento: 2,9 minutos

Com 2 caixas

Tempo médio de atendimento do cliente: 127,498 minutos

Desvio padrão do tempo de atendimento: 1,46 minutos

Com 3 caixas

Tempo médio de atendimento do cliente: 85,854 minutos

Desvio padrão do tempo de atendimento: 0,974 minutos

A quantidade de caixas afeta diretamente o tempo de espera na fila. Embora o tempo médio de atendimento individual (µ) não mude, o tempo total que cada cliente passa no sistema é significativamente reduzido. Aumentar o número de caixas cria um paralelismo no processo, dividindo a fila e diminuindo o tempo de espera para cada cliente. Com filas menores, o tempo médio que cada pessoa leva para ser atendida diminui drasticamente.
__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
3) Variação de σ (desvio padrão) e seu impacto.
σ = 0,25: Desvio padrão das médias = 0,069 minutos

σ = 1,0: Desvio padrão das médias = 0,267 minutos

σ = 2,0: Desvio padrão das médias = 0,549 minutos
___________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
#4) Por que este simulador é considerado estocástico?#
Este simulador é estocástico porque suas saídas variam com base em dados gerados de forma aleatória, mesmo com valores fixos de média e desvio padrão. Essa aleatoriedade é crucial para refletir situações reais, onde o tempo de atendimento em um supermercado nunca é totalmente previsível. Fatores imprevisíveis na vida real — como um cliente esquecendo um produto ou um problema no caixa — são representados por essa variabilidade aleatória no código, tornando a simulação mais realista do que um cálculo puramente determinístico.
