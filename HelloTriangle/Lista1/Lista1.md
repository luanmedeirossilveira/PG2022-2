# Lista de Exercícios 1 – Processamento Gráfico
## Introdução à OpenGL Moderna – Shaders & Buffers

1. O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável
da versão atual que trabalhamos em aula e o que eles processam?

```
O GLSL é adaptado para uso com gráficos e contém recursos úteis especificamente direcionados à manipulação de vetores e matrizes.

São dois principais e obrigatórios para o pipeline que são o Vertex Shader, com o objetivo de descrição do tratamento da vértice e o Fragment Shader, que tem como objetivo o tratamento de uma área.
```

2. O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?

```
São os elementos mais básicos para criação, como GL_POINTS, GL_LINES, GL_TRIANGULOS...

Armazenamos os vértices em um array tipo float.
```

3. Explique o que é VBO, VAO e EBO, e como se relacionam (se achar mais fácil, pode fazer
um gráfico representando a relação entre eles).

```
Vertex Buffer Object (VBO): Buffer que armazena um array de dados (posição, vetores, cores) na memória GPU, permitindo uma renderização mais rápida. 

Vertex Array Object (VAO): Liga dos atributos de um vértice, definindo o uso do VBO, localização e o formato desses dados.

Element Buffer Object (EBO): Buffer para o armazenamento de índices.
```

4. Analise o código fonte do projeto Hello Triangle. Localize e relacione os conceitos de
shaders, VBOs e VAO apresentados até então. Não precisa entregar nada neste exercício.
```
```

5. [Finalizado]
    5A. [Finalizado]
    5B. [Finalizado]
    5C. [Finalizado]
    5D. [Finalizado]

6. [Finalizado]
    6A. [Finalizado]
    6B. [Finalizado]
    6C. [Finalizado]
    6D. [Finalizado]
    6E. [Finalizado]

7. [Implementando]

8. Considerando o seguinte triângulo abaixo, formado pelos vértices P1, P2 e P3,
respectivamente com as cores vermelho, verde e azul.
    - Descreva uma possível configuração dos buffers (VBO, VAO e EBO) para
    representá-lo.
    - Como estes atributos seriam identificados no vertex shader?

9. [Implementando]

10. [Implementando]
