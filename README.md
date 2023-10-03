# Modelado, análisis, simulación y control de un fenómeno vibratorio

Elabora:
* Adrián Augusto Ferrer Orgaz
* Carlos de Jesús Ávila González
* Elisa Maria Bonilla Martín
* Enrique Maldonado Chavarría

Se modeló matemáticamente el desplazamiento lateral de edificios con múltiples grados de libertad, con un sistema de ecuaciones diferenciales lineales, frente a excitación sísmica harmónica simulada como una onda sinodal. En el análisis realizado de este modelo para 2 pisos y un techo (3 masas, 3 grados de libertad), se observó un sistema estable interna y externamente, cuya frecuencia de resonancia con mayor impacto a tiempo infinito genera una escalamiento en el desplazamiento lateral de las masa de $26.71~dB$. Posteriormente, se analizaron modelos de control activo (control lazo cerrado), con el objetivo de reducir el escalamiento violento de esta frecuencia de resonancia. Se estudiaron los modelos de *Actuadores Hidráulicos* , *Masa de Amortiguamiento Activo* y el diseño de leyes de control con el *Algoritmo de Riccati de Control Óptimo*. Se montaron ambos modelos en conjunto y por separado en el modelo sin control y se analizó el comportamiento frente a la frecuencia de resonancia destacada. Cada implementación de control tuvo el efecto esperado, una reducción satisfactoria en el escalamiento frente a la frecuencia de resonancia. El modelo con mejor atenuación del efecto resultó ser aquel que combina ambas técnicas de control activo.

## Vínculos a contenido
<a href="https://drive.google.com/file/d/1rbHz0ZpLgKJfkT1pJHuFUL6v9EprXMnV/view?usp=sharing" target="_blank">Reporte Escrito</a>

<a href="https://github.com/AdrianFO-16/ModelacionMatematicaControlDeSismos" target="_blank">Repositorio en GitHub</a>

<a href="https://drive.google.com/drive/folders/1xlmUVo03crHmguR0dhqxHtzx9yCDZwHR?usp=sharing" target="_blank">Carpeta de Google Drive</a>

<a href="https://adrianfo-16.github.io/ModelacionMatematicaControlDeSismos" target="_blank">Página de Simulaciones</a>
