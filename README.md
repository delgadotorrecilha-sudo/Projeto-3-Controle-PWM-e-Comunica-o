# Projeto-3-Controle-PWM-e-Comunica-o
Este projeto tem como objetivo exercitar a programação de microcontroladores de 32
bits por meio do desenvolvimento de uma aplicação prática utilizando a plataforma ESP32
DevKit. Serão explorados conceitos de comunicação serial e modulação por largura de pulso
(PWM), além da utilização de bibliotecas otimizadas para o controle de periféricos e GPIOs,
incluindo UART, I2C, display OLED, sensor touch, Wi-Fi e Bluetooth. O desenvolvimento e
a validação do sistema serão realizados com o auxílio do ambiente de simulação virtual
Wokwi, permitindo testar funcionalidades de hardware e software de forma eficiente. Durante
a execução do projeto, também foram analisadas e discutidas decisões de engenharia
relacionadas à escolha do microcontrolador, ao aproveitamento dos recursos de hardware e
software disponíveis, à otimização do consumo energético e aos desafios encontrados durante
a implementação e integração dos diferentes módulos do sistema.

Luís Carlos Delgado Torrecilha - 15472530 
Beatriz Fonseca Silva - 15653959

Parte 1 - https://wokwi.com/projects/468551935017966593

Parte 2 - 1 - https://wokwi.com/projects/468574746974776321

Parte 2 - 2 - https://wokwi.com/projects/468577686928329729

O sistema lógico, o controle de estado e a configuração da biblioteca nativa mcpwm.h foram implementados e validados com sucesso através do monitoramento de dados via barramento I2C (Display OLED) e UART (Serial). No entanto, devido à recente migração do simulador Wokwi para o ESP32 Arduino Core v3.x, a renderização gráfica de atuadores físicos (motores e LEDs) atrelados às GPIOs controladas pela API legada do MCPWM apresenta falhas de compatibilidade visual. O funcionamento elétrico do microcontrolador, contudo, foi comprovado pela exatidão do processamento dos duty cycles exibidos nos periféricos de comunicação.
