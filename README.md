Confira uma sugestão de README para o seu projeto:
Jogo de Corrida Simples

Um jogo de corrida básico desenvolvido em p5.js, onde três jogadores competem para alcançar a linha de chegada.
Como Jogar

    Acesse o Jogo: Abra o arquivo index.html em seu navegador ou execute o código em um ambiente p5.js (como o editor online).
    Comece a Correr:
        Pressione a tecla "a" para mover o jogador 1 (😎).
        Pressione a tecla "s" para mover o jogador 2 (❤️).
        Pressione a tecla "d" para mover o jogador 3 (👽).
    Vencedor: O primeiro jogador que cruzar a linha de chegada branca (localizada à direita da tela) vence a partida. O jogo será pausado e o nome do vencedor será exibido.

Funcionalidades

    Três Jogadores: Controle três personagens diferentes.
    Controles Simples: Movimento baseado em teclas específicas.
    Linha de Chegada: Uma linha de chegada visualmente distinta.
    Detecção de Vencedor: O jogo identifica automaticamente o primeiro jogador a cruzar a linha e declara o vencedor.
    Feedback Visual: A cor de fundo muda dependendo se a janela do jogo está em foco ou não.

Tecnologias Utilizadas

    p5.js: Uma biblioteca JavaScript para programação criativa, com foco em desenho e interatividade.

Estrutura do Código

    setup(): Inicializa o canvas do jogo.
    draw(): A função principal que é executada continuamente, chamando outras funções para atualizar o estado do jogo.
    ativaJogo(): Define a cor de fundo com base no foco da janela.
    desenhaJogadores(): Desenha os três jogadores na tela.
    desenhaLinhaDeChegada(): Desenha a linha de chegada.
    verificaVencedor(): Checa se algum jogador atingiu a linha de chegada e exibe o vencedor.
    keyReleased(): Captura os eventos de liberação de tecla para mover os jogadores.

Como Rodar Localmente

    Certifique-se de ter um ambiente para executar arquivos HTML e JavaScript (um navegador web já é suficiente).

    Copie o código fornecido para um arquivo .js (por exemplo, sketch.js).

    Crie um arquivo index.html na mesma pasta e inclua o p5.js e o seu arquivo sketch.js.
