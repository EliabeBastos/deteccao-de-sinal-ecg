# Trabalho final microprocessado 2022 - Projessor Jardel

# Integrantes

Eliabe Bastos Dias - 509723

Igor Ferreira Vasconcelos - 509138

Weatherly Moura Albuquerque - 511792 

Gabriel Pinheiro Palitot Pereira - 511884

# Componentes

1 sensor ECG

1 STM32F070F6P6

1 protoboard

1 ESLink

1 display

# Descrição

  O projeto consiste na aquisição do sinal biológico cardíaco (ECG), a partir do módulo AD8232, carinhosamente apelidado de "kit ECG". Dito kit consiste de uma série de amplificadores operacionais que permitirão a transformação de tensões da ordem de nV em tensões entre 0V e 3.3V, perfeito para leitura pelo conversor A/D do STM32.
  O STM irá enviar a leitura do sinal para um terminal em um computador, via USART, por meio de um conversor USB/serial. Os dados serão enviados para um programa em Python que realizará a plotagem e o processamento digital (filtragem) do sinal.

As configurações do STM32 estão abaixo:

A amostragem do projeto final é:

