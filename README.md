Este projeto utiliza o Raspberry Pi Pico e a biblioteca WS2812 para criar uma interface interativa com um display SSD1306, botões e LEDs RGB. O código realiza animações, responde a interações dos usuários e exibe números em uma matriz de LEDs WS2812.

Demonstração
Aqui está o vídeo de demonstração do funcionamento do projeto:
https://youtu.be/oUu_xfhffV0

Descrição
Este projeto tem como objetivo controlar um display OLED SSD1306 e uma matriz de LEDs WS2812 usando um Raspberry Pi Pico. Ele também possui dois botões para controlar LEDs RGB e interage com o usuário por meio de entradas seriais.

Funcionalidades:
Exibição do nome "Matheus Vinicius Vidal" no display OLED com animações.
Controle de LEDs RGB (vermelho, verde e azul) através de botões.
Recepção de números via entrada serial e exibição de números na matriz de LEDs WS2812.
Funcionalidade de debounce para evitar múltiplos acionamentos indesejados dos botões.
Componentes Usados
Raspberry Pi Pico
Display SSD1306 (I2C)
Matriz de LEDs WS2812
LEDs RGB
Botões para controle de LEDs
Como Funciona
Animação no Display:
O nome "Matheus Vinicius Vidal" é exibido no display OLED com animações de fundo.
Controle de LEDs:
O botão A controla o LED verde.
O botão B controla o LED azul.
Exibição na Matriz de LEDs WS2812:
O número inserido via Serial Monitor será exibido na matriz de LEDs WS2812. Cada número de '0' a '9' corresponde a uma cor em uma matriz de LEDs.
Como Executar
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/Matheusvinici/Atividade0302
Carregue o código no seu Raspberry Pi Pico usando o Thonny IDE ou outro editor compatível com o Raspberry Pi Pico.

Conecte o seu Raspberry Pi Pico à porta USB do computador e abra o monitor serial.

Pressione os botões A ou B para controlar os LEDs. Envie números de 0 a 9 via entrada serial para ver a exibição na matriz de LEDs.
