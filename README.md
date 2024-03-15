# Mundo dos Blocos utilizando python e arquivos STRIPS (Stanford Research Institute Problem Solver).

O problema do mundo dos blocos consiste em um conjunto de blocos colocados sobre uma
mesa (infinita em largura) onde cada bloco pode ser empilhado um sobre o outro através de
um braço robótico.

# Algumas restrições:

1. O braço robótico só pode segurar um bloco de cada vez;
2. O braço robótico só pode pegar um bloco se ele não possuir nenhum outro bloco acima;
3. O braço robótico, se estiver segurando um bloco, pode colocá-lo sobre a mesa ou sobre outro bloco (que por sua vez não tem outro bloco em cima);
4. Apenas um bloco pode estar imediatamente acima de outro;
5. Podemos ter uma quantidade qualquer de blocos;

Com as restrições acima, o problema do mundo dos blocos consiste em determinar os
passos, dada uma configuração inicial de blocos, para se obter uma configuração final.

# Como rodar:

1. Clone esse repositório.
2. Crie um virtualenv com Python 3.
3. Ative o virtualenv.
4. Instale o "python-sat" com o pip.
5. Rode o comando "python3 main.py instancias_mundo_dos_blocos/(QUALQUER STRIP QUE TIVER NESSA PASTA)"

# Observações:

Só lembrando que para Instâncias grandes pode acontecer de demorar mais de 1 hora para encontrar a solução.
