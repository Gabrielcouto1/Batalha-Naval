# Batalha-Naval
 Trabalho 1 de Programação procedimental
O programa, segundo orientações do professor, foi escrito em C e sem utilização de funções além da main()

O programa opera um jogo simples de batalha naval com dois modos, PLAY e CORR. Quando no modo CORR,
todas as naves serao mostradas na tela. O oceano inicial aparece na tela, o usuário deve digitar qual
setor do oceano ele deseja atirar (ex:A1). Se ele digitar algum caractere inválido, isso é escrito na
tela e o programa encerra. Se ele atirar em algum setor ja atirado ele deve atirar novamente sem perder
torpedo algum. Se ele acertar um submarino, a mensagem de acerto é escrita na tela e o oceano aparece
novamente com um '*' no lugar que ele acertou. Em seguida mostra o que resta no seu inventário. Caso ele
erre o tiro, aparece uma mensagem informando que ele afundou o torpedo no mar e um 'W' eh escrito nesse setor do oceano.
O programa encerra se: o usuario acabar com todos destruidores e submarinos (escreve na tela que ele ganhou 
o jogo) ou se o usuario nao tiver mais torpedos e ainda existir naves no oceano(escreve na tela que ele perdeu
o jogo).
    Se antes de iniciar o jogo, o usuario inserir uma quantidade de submarinos, torpedos e destruidores que
impossibilitam o jogo de ser jogado, o programa se encerra e escreve a mensagem de erro na tela.
