---
title: "Análise de Simulating Physics with Computers"
tags:
  - analise
  - resumo
---
# Análise de Simulating Physics with Computers
>Título: **Simulating Physics with Computers**[^1]  
>Autor: Richard P. Feynman  
>PDF:[Análise de Simulating Physics with Computers.pdf]( <../Pdfs/Análise de Simulating Physics with Computers.pdf>)  

[^1]: Feynman, Richard P.. Simulating Physics with Computers. **International Journal of Theoretical Physics**, vol 21, n. 6/7, 1982. Disponível em: http://link.springer.com/10.1007/BF02650179. Acesso em 16 de setembro de 2026.
## Resumo
Dentro da computação tradicional, a discretização do mundo real é necessária para que os computadores comuns consigam fazer previsões e simulações do mundo físico, ou seja, para que um computador consiga fazer qualquer tipo de simulação física, deve-se assumir que a Humanidade saiba de todas as Leis Físicas e que seja possível implementa-las. Entretanto, quando se trata de simular o mundo físico em sua totalidade, a computação tradicional afirma que não é possível que uma única máquina consiga fazer tal façanha.

Feynman propõe um experimento mental para descobrir qual tipo de computador conseguiria simular a Física. Inicialmente, ele discute sobre qual Física deve ser simulada: a Física Clássica ou a Física Quântica, reforçando que, neste experimento, o computador deverá ser capaz de simular _**exatamente**_ a natureza, não apenas chegar à aproximações do comportamento do mundo. Isso implica que tudo dentro de um volume finito de tempo e espaço precisa ser capaz de ser analisado com um número finito de operações lógicas, algo que não ocorre segundo as teorias físicas atuais, que tratam o espaço e suas medidas como capazes de ser infinitesimalmente pequenos ou infinitamente grandes. Dessa forma, chega-se a conclusão que é necessário que aja uma mudança nas Leis Físicas e tem-se já uma sugestão do que poderia ser feito para alterá-las: considerar o espaço como uma rede simples e discreta e que o tempo passa descontinuamente. 

Feynman, então, sugere que imaginemos como seria um mundo físico que segue essa "nova" lei física e cita alguns dos problemas que surgem com essa mudança para a simulação computacional que é o fato que a velocidade da luz se tornaria ligeiramente dependente na direção e a possibilidade de existir outras anisotropias na Física aparentes em experimentos, ainda que pequenas. Como o conhecimento físico sempre será incompleto, ser capaz de prever algo consistentemente a partir de todos dados conhecidos e sugerir um novo fato ainda não explicado é algo bom, mas a questão não é se existe anisotropias nem se poderíamos fazer algum experimento para prever esse comportamento, mas sim quão anisotrópico ele seria. Independente de quanto seja  o nível de anisotropia, o experimento com o átomo de lítio sugere que o verdadeiro nível é menor do que o proposto.

Outra sugestão feita foi que as Leis Naturais são reversíveis, enquanto as leis computacionais não, o que não é verdade. As leis computacionais podem ser reversíveis, algo muito útil, especialmente no estudo das relações entre as leis da computação e as leis físicas, abrindo a possibilidade de nos mostrar algo novo em ambas as áreas.

O autor propõe outra regra para esses computadores, além de ser capaz de simular perfeitamente o mundo físico, o tamanho real dessas máquinas deve ser proporcional ao tamanho do espaço-tempo simulado. "Se dobrar o volume do espaço e tempo significa que eu preciso de um computador _exponencialmente_ maior, eu considerarei contra as regras (...).", segundo ele.

A primeira simulação que ele propõe é a simulação do tempo. Ele assume o tempo como discreto (já que não temos como medir com precisão infinita), em uma escala de $10^{-27}$ segundos — maior intervalo de tempo que não causa discrepâncias com os dados experimentais. Na simulação tradicional, como em um autômato celular, o computador varia de estado em estado, o que envolve conceitos de tempo, ainda que intuitivos, ou seja, o computador imita a passagem de tempo ao invés de simulá-la. O autor então questiona se seria possível simular o tempo e não apenas imitá-lo, sugerindo que usemos a visão de espaço-tempo do mundo, com todos os pontos do espaço e do tempo já "plotados", gerando mais uma regra para o "computado": Para cada estado $s_i$ em um ponto $i$ do espaço-tempo é uma função $F_i (s_j,\ s_k, ...)$ dos estados dos pontos $\{j,\ k, ...\}$ nas redondezas de $i$:

$$s_i = F_i (s_j,\ s_k, ...)$$

![F_i(s_j, s_k, ...)DosEstadosDosPontos.png](<../Imagens/F_i(s_j, s_k, ...)DosEstadosDosPontos.png>)

Entretanto, se nesta função o valor de $s_i$ — o valor de $F_i(j, \ k, ...)$ — for dependente apenas de alguns pontos localizados antes do tempo $i$, isso é um autômato celular normal, já que ela calcula um ponto a partir de pontos anteriores. Feynman pede para que consideremos um tipo mais abrangente de computadores, já que a função real pode ser mais geral, como no caso de uma generalização maior de interligação de pontos do espaço-tempo, por exemplo, o $F_i$ depender de todos os pontos no passado e no futuro. Ele cita esse exemplo porque múltiplas equações matemáticas podem ser simplificadas se considerarmos que os elétrons e os pósitrons possam voltar no tempo e que outras coisas que conectem objetos avancem ou voltem no tempo. Isso levanta a questão de se existiria um algoritmo capaz de ser resolvido – computadorizado – caso esse computador seja projetado. Se supormos que a função $F$ é conhecida e é função das variáveis no passado e no futuro , pode ser que não seja possível achar números que a satisfaçam. No caso do autômato celular, a $F$ tem raiz, porque a partir de uma linha você consegue achar a próxima e a depois dessa e assim por diante de forma organizada, mas o autor incentiva questionar se existiriam circunstâncias em que $F$ não é notável, ou seja, que a função não seja facilmente organizada de forma clara, talvez apenas reduzindo-a à uma aproximação, mas o autor diz que isso é um outro tipo interessante de computação.

Um dos participantes pergunta se isso não reduziria a função à um problema de contorno ao invés do inicialmente proposto problema de valor inicial, e Feynman responde que sim, reduziria, mas reforça que ele está descrevendo o próprio computador nesse momento.


