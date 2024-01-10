# 17W Suction Control on STM32F103C8T6 MCU

# Clock Configuration
* SYSCLK: 72 MHz
* Use 8 MHz High Speed External (HSE) clock


# GPIO Configuration
* PB0:
  * User Label: Suction_Enable
  * GPIO output level: Low
  * GPIO mode: Output Push Pull
  * GPIO Pull-up/Pull-down: No pull-up and pull-down
  * Maximum output speed: Low


# UART Configuration
* USART1
  * Mode: Asynchronous
  * Pins
    * PA9: USART1_TX
    * PA10: USART1_RX
  * Configuration
    * Baud Rate: 9600 Bits/s
    * Word Length: 8 Bits (including Parity)
    * Parity: None
    * Stop Bits: 1
    * Data Direction: Receive and Transmit

 
# IDWG Configuration
* Use 40 kHz LSI RC clock 
* Timeout: 1 second
