# Controle Fuzzy para Desvio de Obstáculos em Robótica Móvel

Este projeto consistem em um sistema de controle de desvio de obstáculos a ser utilizado em robôs sendo aplicado à lógica fuzzy.

## Especificação do sistema fuzzy

O robô possui um sensor frontal (distância até o obstáculo à frente) e dois sensores laterais (direito e esquerdo), cuja
diferença indica de que lado o obstáculo está mais próximo. A saída do sistema é o ângulo de correção da direção do
robô.

### Variável de entrada 1 — Distância frontal ao obstáculo (d)

Universo de discurso: **d ∈ [0, 100] cm**. Termos linguísticos: **{Perto, Média, Longe}**

<img width="434" height="252" alt="image" src="https://github.com/user-attachments/assets/742680b5-4d74-460f-b881-f3ef7def0e8b" />

### Variável de entrada 2 — Assimetria lateral (a = d_dir − d_esq)

Universo de discurso: **a ∈ [−50, 50] cm** (valores negativos = obstáculo mais próximo do lado direito). Termos
linguísticos: **{Negativa, Zero, Positiva}**

<img width="434" height="252" alt="image" src="https://github.com/user-attachments/assets/40eed0d9-a433-4fb2-a756-989b8a918716" />
