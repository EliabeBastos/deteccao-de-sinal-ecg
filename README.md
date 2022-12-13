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

 O projeto basicamente consiste em adquirir um sinal ECG de um kit de leitura e utilizar
o microcontrolador STM32, inicialmente, para realizar sua conversão para sinal digital. Em
seguida, a partir de uma placa ESP32, iremos transmitir esse sinal para um display,
contanto a quantidade de batimentos por minuto. 

  Em um primeiro momento o processador STM32
só será utilizado para a realização da conversão para sinal digital e conseguir comandar o
sistema de WIFI da ESP32, porém, como já dito, essa é apenas uma função inicial, estando
aberto para novas funções conforme o desenvolvimento do projeto. Para uma descrição mais detalhada, temos que a conversão, logicamente vai ser
realizada a partir do conversor analógico-digital da STM.


As configurações do STM32 estão abaixo:

A amostragem do projeto final é:

