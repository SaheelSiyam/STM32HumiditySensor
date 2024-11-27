# STM32HumiditySensor

//This device is a humidity sensor for plants that contains the following specifications

//Functional: 
//
//1.
//Check to make sure the LED is red when humidity is low
//Dry soil environment; no water
//When the LED is red, pass. When the LED shows a different color, fail.

//2.
//Check to make sure the LED is green when humidity is medium
//Wet soil environment; spray little amount of water
//When the LED is green, pass. When the LED shows a different color, fail.

//3.
//Check to make sure the LED is blue when humidity is high
//Watery soil environment; pour great amount of water
//When the LED is blue, pass. When the LED shows a different color, fail.

//
//
//
//

//Technical: 

//Uses DHT22 Humidity and Temp sensor, with RGB LED
//Communication between the two STMs occurs with USART half duplex communication on shared RX/TX lines
//
//
//
//
