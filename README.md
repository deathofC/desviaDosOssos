Dodge the Bones é um jogo 2D criado com Pygame, inspirado nas batalhas de Undertale. O jogador controla um pequeno personagem que deve desviar de ossos que se movem horizontalmente pela 
tela. O objetivo é sobreviver o máximo possível, ganhando 1 ponto por osso evitado, enquanto a velocidade dos ossos aumenta progressivamente.

🕹️ Mecânicas do Jogo
Movimento:
Use as teclas W/S ou setas cima/baixo para se mover na vertical.

Tipos de ossos:

Curto (branco): atinge se colidir.

Longo (branco): maior área de colisão.

Azul: só causa dano se você estiver se movendo ao tocá-lo (como no Undertale).

Vida:
O jogador começa com 5 pontos de vida e perde 1 ao ser atingido.

Pause:
Pressione barra de espaço para pausar o jogo (a música também pausa).

Sans Voador:
Um sprite do Sans voa horizontalmente pela parte superior da tela.
A cada 60 pontos, ele para de voar e fala uma frase ameaçadora com voz masculina, como:

“Você já está cansado?”

“Você não vai conseguir”

“Você não vai desviar do próximo osso”
A música também pausa por 2 segundos enquanto ele fala.

🗣️ Recursos Especiais
Reconhecimento de voz:
O jogador diz seu nome em voz alta no início do jogo, que será usado para registrar a pontuação.

Ranking:
Um ranking salva as 5 maiores pontuações com data, nome e pontuação.

Efeitos Visuais:

Uma linha branca horizontal representa a "zona segura" onde os ossos começam a aparecer.

Um círculo amarelo pulsante no canto superior direito representa a lua, que aumenta e diminui de tamanho lentamente.

🔊 Áudio
Músicas diferentes para:

Menu

Jogo

Game Over

Efeito sonoro de dano

Voz sintetizada do Sans via pyttsx3

⚙️ Tecnologias Usadas
Python 3.13

Pygame

pyttsx3 (voz do Sans)

speech_recognition (entrada de nome por voz)

cx_Freeze (para gerar o .exe)

testador: Adriano Cézar Tessaro Júnior 1138080
