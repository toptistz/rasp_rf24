lib_nrf24
=========

Python2/3 library for NRF24L01+ Transceivers

V0.3 beta

For Raspberry Pi and virtual-GPIO.
NRF24: strictly 3.3V supply!! Although logic pins are 5V tolerant.

This is BETA only so far.
Everything has worked earlier, send, receive, including two RF24 on one host, and including RPI, virtual-GPIO and regular arduino sketch, all talking to each other.

But recent testing has been only LIBRARY plus "example-nrf24-pair.py" on virtual-GPIO, so other parts are yet to be re-verified. 

Setting Raspberry Pi

  mkdir NRF24L01
  
  cd NRF24L01

  git clone https://github.com/topclassic/lib_rf24
  
  cd lib_rf24
  
  cp lib_rf24.py ~/Desktop/NRF24L01
  
