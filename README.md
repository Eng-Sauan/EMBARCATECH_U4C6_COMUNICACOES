# EMBARCATECH_U4C6_COMUNICACOES
# Controle de LEDs, Display OLED e UART com BitDogLab (RP2040)

Projeto que utiliza a placa BitDogLab (RP2040 - Pi Pico W) para controlar LEDs, um display OLED SSD1306 e comunicação UART, permitindo interação por botões físicos e exibição de caracteres recebidos via USB.

O código configura os GPIOs para LEDs e botões, implementa debounce para evitar leituras indevidas e utiliza interrupções para detectar cliques. O display OLED exibe o estado dos LEDs e caracteres recebidos pela UART. Além disso, números de 0 a 9 podem ser usados para atualizar uma matriz de LEDs. A comunicação UART permite monitoramento em tempo real, tornando o projeto ideal para aprendizado e experimentação com periféricos no RP2040.

LINK VÍDEO: https://youtu.be/Tw_QuKtBo_Y