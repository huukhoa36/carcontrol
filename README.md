# REMOTE CAR CONTROL
I use KeilC v5 + STM32CubeMX
# Pin connection:

# TX:

STM32F103C8T6 - Joystick

PA1 - VRx

PA2 - VRy

STM32F103C8T6 - NRF24L01

PA6 - CE

PA7 - CSN

PA3 - SCK

PA4 - MOSI

PA5 - MISO

# RX:

STM32F103C8T6 - L298N

PA15 - EN1

PA3 - EN2

PA4 - IN1

PA5 - IN2

PA6 - IN3

PA7 - IN4

STM32F103C8T6 - NRF24L01

PA1 - CE

PA2 - CSN

PA3 - SCK

PA4 - MOSI

PA5 - MISO
