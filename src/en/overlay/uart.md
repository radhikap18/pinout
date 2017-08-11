<!--
---
name: UART
class: interface
type: pinout
description: 96Boards UART pins
pincount: 6
pin:
  '3':
    name: UART0_CTS
  '5':
    name: UART0_TxD
  '7':
    name: UART0_RxD
  '9':
    name: UART0_RTS
  '11':
    name: UART1_TxD
  '13':
    name: UART1_RxD
-->
#UART - Universal Asynchronous Receiver/Transmitter

UART is an asynchronous serial communication protocol, meaning that it takes bytes of data and transmits the individual bits in a sequential fashion.

Asynchronous transmission allows data to be transmitted without the sender having to send a clock signal to the receiver. Instead, the sender and receiver agree on timing parameters in advance and special bits called 'start bits' are added to each word and used to synchronize the sending and receiving units.
