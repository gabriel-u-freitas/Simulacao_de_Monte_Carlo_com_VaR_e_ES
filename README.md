# Simulacao_de_Monte_Carlo_com_VaR_e_ES
Este repositório contém uma implementação em Python de uma simulação de Monte Carlo aplicada a séries financeiras, com foco na mensuração de risco de portfólios por meio das métricas Value at Risk (VaR) e Expected Shortfall (ES).

O projeto foi desenvolvido com fins educacionais e analíticos durante meu período no núcleo de Riscos & Derivativos do Clube de Finanças Esag & UFSC, seguindo práticas comuns utilizadas em gestão de risco, finanças quantitativas e engenharia financeira.

A simulação de **Monte Carlo** é uma **técnica estatística que utiliza processos aleatórios para modelar possíveis cenários futuros**. No contexto financeiro, ela permite simular múltiplos caminhos para os retornos de ativos e, a partir dessas simulações, estimar a **distribuição de perdas e ganhos de um portfólio**

Com base nessa distribuição, o código calcula duas métricas amplamente utilizadas em gestão de risco:
1. **Value at Risk (VaR)**: perda máxima esperada para um determinado nível de confiança e horizonte de tempo.
2. **Expected Shortfall (ES)**: perda média esperada nos piores cenários, ou seja, condicionalmente às perdas que excedem o VaR.
