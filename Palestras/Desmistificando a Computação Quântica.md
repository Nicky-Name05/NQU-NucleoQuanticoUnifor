---
tags:
  - palestra
---
# Desmistificando a Computação Quântica
>Palestra por Karoline Rodrigues Lima[^1]  
PDF: [Desmistificando a Computação Quântica](<Desmistificando a Computação Quântica.pdf>)  
Slide: [Palestra Desmistificando a Computação Quântica](<Pdfs/Palestra Desmistificando a Computação Quântica.pdf>)

[^1]:LIMA, KAROLINE RODRIGUES; SILVA, PAULO HENRIQUE PEREIRA. **Desmistificando a Computação Quântica**. Universidade de Fortaleza, Fortaleza, CE, 30 set. 2026.
## O que é quântica?
A quântica é associada a equações confusas e/ou pouco intuitivas e por isso acaba tendo coisas místicas associadas a ela. A diferença entre ciência e pseudociência pode ser feita através da procura de provas, feitas por pessoas ou comprovado por artigos.
## Física quântica
Nasce de discrepâncias entre previsões da física clássica e os experimentos
### Radiação de corpo negro
Todos os corpos produzem radiação eletromagnética devido a sua temperatura (radiação térmica) e o corpo negro é o modelo ideal que absorve toda a energia que recebe e emita um  espectro de caráter especifico.

> [!IMPORTANT]
>  Mas como cada corpo produz um espectro dependente de sua temperatura?
> Em experimentos, a intensidade não aumentava exponencialmente que nem previa a física quântica.
>Plank soluciona isso ao considerar que a energia é quantizada e em altas temperaturas é difícil que aja troca de temperatura.

### Efeito fotoelétrico

quando uma luz incide sobre um metal elétrons são ejetados

>[!IMPORTANT]
>Mas é a intensidade da luz ou a frequência da luz que fazem eles serem ejetados?
É a frequência que é quem determina isso, provado por Einstein, que propôs que a luz é composta por quantons (fótons atualmente).
>
> $$ energia = constante \; de \; plank * frequência$$
### Comportamento de onda-partícula

#### Comportamento de onda
O experimento de young mostra que a luz age como onda, tendo interferência notável (formação de onda).
##### Comportamento de partícula
Efeito fotoelétrico, os fótons tem "peso".
Em 1924, foi teorizado que partículas tem comportamentos ondulatórios

### Superposição
Se supormos que os elétrons são bolinhas, a formação de franjas é indicativo de interação das partículas. Como os elétrons são probabilidades, enquanto eles não são observados, aua posição é desconhecida e "existe" em ambos os estados até ser visto.

## Emaranhamento
O resultado/ estado de uma partícula quântica emaranhada com outra muda o estado junto com ela.
# Computação Quântica

## Diferença com a clássica

| classica                                     | quântica                                                        |
| -------------------------------------------- | --------------------------------------------------------------- |
| bit(1 - passa energia/ 0- nao passa energia) | qBit (um vetor que varia de 0 a 1 ou uma super posiç!ao desses) |
| 0 / 1                                        | $\ket \Psi \alpha \ket 0 \beta \ket 1$                          |
| Portas AND (1,1 -> 1)                        |                                                                 |
| Porta NOR (0 -> 1)                           |                                                                 |
| Porta OR (1,1 \| 1,0 \| 0,1-> 1)             |                                                                 |
| Porta XOR (1,0 \| 0,1-> 1)                   |                                                                 |
|                                              |                                                                 |

## Algoritmos quânticos
### Shor
Fatoração de números: achar uma combinação de primos que gera um numero, é usado para cyber segurança

## Possibilidades

Saúde: simulação de moléculas e mapeamento de genomas
Computação: Cyber segurança

## Desafios
- Ruido e perda de coerência
- Aumento de escala
- Correção de erro
- Vantagem pratica: ainda é necessário identificar aplicações em que um método quântico é melhor que que um clássico
