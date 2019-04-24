#                                           Computação-Gráfica-T1

**link trabalho 2(pipeline):** https://github.com/MatheusGSantos/Computacao_Grafica-T2

# Objetivo
Com o uso da linguagem C/C++ e OpenGL, rasterizar um triângulo, dados seus vértices, interpolando as cores dos vértices para formar a cor das arestas.

# Estratégias
Foi utilizado o algoritmo de Bresenham para desenhar as arestas do triângulo. O algoritmo consiste em realizar um calculo matemático para calcular constantes e uma variável de decisão. Após calculada a variável de decisão, o processo fica pouco custoso, já que o x e y do próximo ponto serão definidos com base na variável de decisão que é incrementada ou decrementada de acordo com seu valor anterior. Para a interpolação dos pontos, foi utilizado o algoritmo de Henri Gouraud, que usa as distâncias entre as extremidades da aresta e a distância entre o pixel atual e final para determinar uma constante, que será utilizada numa função, que usa as cores das extremidades, para determinar a cor do próximo pixel.
