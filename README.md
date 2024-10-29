# PonderadaSemaforo

## Relatório de Prática
Para a conexão utilizei uma protoboard e o arduino UNO conectado a entrada 11 do meu notebook. Encaixei os leds nos espaços do suporte para simular um semáforo e aos pinos dos LEDs conectei jumppers macho-fêmea e depois os conectei a protoboard tanto ao fluxo negativo alimentado pelo jumpper conectado ao GND do arduíno quanto ao fluxo positivo alimentado pelas outras portas (11, 12 e 13), fluxo esse que foi limitado por 3 resistores (um resistor para cada cabo jumpper). Para ir além, levei em consideração que o semáforo era do tipo de parada de carros, ou seja: vermelho - pare, amarelo - atenção, verde - siga. Logo, decidi adicionar um buzzer que faz barulho por um segundo ao semáforo acionar a cor vermelha. 

Após preparar o protótipo físico, no software arduino, desenvolvi o código por etapas de cores o que deu "vida" ao projeto. 
