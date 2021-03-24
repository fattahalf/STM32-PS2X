# PS2X :: STM32F4 (Nucleo F429ZI)
Interfacing PS2 Wireless Controller with STM32 (Nucleo-F429ZI) with STM32CubeIDE

Details :
1. This project use SPI1 to interface with PS2 Wireless Receiver.
2. The SPI data size is 8bit, LSB first, with baud rate 62,5 kB/s, HIGH Clock Polarity, and 2 edge Clock Phase.
3. To see the data that received (PSX_RX), use Live expression feature on Debugging Mode in STM32CubeIDE.
4. For more details about the protocol, visit https://store.curiousinventor.com/guides/PS2 and https://gamesx.com/controldata/psxcont/psxcont.htm
