<img src="images/microchiptechnologyinc.jpg" height="60" >

## Objective:
The AVR128DA48 features one 12-bit ADC with accumulation of up to 128 samples per conversion. In this demo, a POT click board will be attached to the mikroBus socket #1 of a Curiosity Nano Adapter and the analog value provided by the potentiometer will be read using AIN3 channel, corresponding to PD3 pin.

## Demo Configuration:
The AVR128DA48 Curiosity Nano Development Board (DM164151) is used as the test platform. The following configurations must be made for this project:
- PD3 pin - Configured as analog input (AIN3)
- ADC0 - Configured in Free Run Mode to accumulate 64 samples
- VREF - Reference voltage for ADC0 set to 2.048V

### AVR128DA48 Curiosity Nano with POT click
<img src="images/ADC_accumulation_setup.jpg" height="500" >

## Required Tools
- Atmel Studio 7.0.2397 or newer
- AVR-Dx 1.0.18 or newer Device Pack
- AVR128DA48 Curiosity Nano (DM164151)
- Curiosity Nano Base (AC164162)
- MikroelEktronika POT click (MIKROE-3402)

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.

## Conclusion:
The demo provides an example of ADC accumulation. Please refer to the AVR128DA48 datasheet for more information or specifications.
