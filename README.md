# STM32 UART Transmit 🚀

This project demonstrates UART transmission on **STM32F446RE** using **HAL drivers**.  
It sends the string `"Hello"` repeatedly every 1 second via **USART2** at **9600 baud rate**.

## 🧩 Hardware
- MCU: STM32F446RE (Nucleo Board)
- UART Port: USART2 (TX - PA2, RX - PA3)
- Baud Rate: 9600

## ⚙️ Software Setup
- **STM32CubeIDE**  
- **HAL Library** enabled for UART2  
- System Clock Source: HSI (16 MHz)

## 💡 Output
Open a serial terminal (like PuTTY or Tera Term or Realterm):
