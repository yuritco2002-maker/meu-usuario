# Controle Fuzzy para Desvio de Obstáculos em Robótica Móvel

Este projeto consistem em um sistema de controle de desvio de obstáculos a ser utilizado em robôs sendo aplicado à lógica fuzzy.

## Especificação do sistema fuzzy

O robô possui um sensor frontal (distância até o obstáculo à frente) e dois sensores laterais (direito e esquerdo), cuja
diferença indica de que lado o obstáculo está mais próximo. A saída do sistema é o ângulo de correção da direção do
robô.

### Variável de entrada 1 — Distância frontal ao obstáculo (d)

Universo de discurso: d ∈ [0, 100] cm. Termos linguísticos: {Perto, Média, Longe}