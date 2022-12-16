# Trabalho final microprocessado 2022 - Projessor Jardel

# Integrantes

Eliabe Bastos Dias - 509723

Igor Ferreira Vasconcelos - 509138

Weatherly Moura Albuquerque - 511792 

Gabriel Pinheiro Palitot Pereira - 511884

# Componentes

1 Sensor ECG (AD8232)

1 Greenpill (STM32F070F6P6) 

1 STlink-32

1 Conversor USB/serial

Bastante paciência

# Descrição

  O projeto consiste na aquisição do sinal biológico cardíaco (ECG), a partir do módulo AD8232, carinhosamente apelidado de "kit ECG". Que consiste em uma série de AMPOPs que permitirão a amplificação de sinais da ordem de nV em sinais entre 0V e 3.3V, perfeito para leitura pelo conversor A/D do STM32.
  O STM irá enviar a leitura do sinal para um terminal em um computador, via USART, por meio de um conversor USB/serial. Os dados serão enviados para um programa em Python que realizará a plotagem e o processamento digital (filtragem) do sinal.

  As configurações do STM32 estão abaixo:
![Configurações STM](https://user-images.githubusercontent.com/105894035/207976082-94a1b0ba-77ae-499d-bbbc-6462a636d375.png)
O kit ECG é este aqui:
![Sensor ECG](https://user-images.githubusercontent.com/105894035/208175327-99f4915a-cbb7-4c3c-bcd3-fa93bc298f33.jpg)
  Lembrando que os eletrodos são descartáveis e normalmente encontrados em lojas de material hospitalar, você NÃO vai encontra-los em lojas de eletrônicos.
  Alimentamos os pinos 3.3 e GND na fonte de alimentação e o pino output vai direto no conversor AD, os pinos LO+ e LO- podem ser deixados flutuando, mas são sinais digitais que dizem se o sensor está captando alguma coisa.

A amostragem bruta do projeto final ficou assim:
![image](https://user-images.githubusercontent.com/105894035/207976850-d7cf4977-ae5b-443b-99fd-41793344f5ed.png)


