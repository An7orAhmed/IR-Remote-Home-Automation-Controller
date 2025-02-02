# IR Remote Home Automation Controller  

## Description  
This project enables remote control of home appliances (lights, fan) using an infrared (IR) remote. Built with Proton Basic for the PIC16F676 microcontroller, it decodes Sony IR signals to toggle relays and adjust fan speed. The system supports up to 7 lights and a PWM-based fan speed controller, providing a flexible automation solution.  

## Features  
- Control 7 relays for lights/appliances (toggle on/off).  
- Adjust fan speed (0-8 levels) via remote commands.  
- Debounce delays to ensure stable toggling.  
- IR signal decoding using Sony protocol.  

## Pin Map (PIC16F676)  
| **Component** | **MCU Pin** | **Physical Pin** |  
|---------------|-------------|------------------|  
| IR Receiver   | PORTC.0     | Pin 10           |  
| Fan (PWM)     | PORTC.1     | Pin 9            |  
| Light 1       | PORTC.2     | Pin 8            |  
| Light 2       | PORTC.3     | Pin 7            |  
| Light 3       | PORTC.4     | Pin 6            |  
| Light 4       | PORTC.5     | Pin 5            |  
| Light 5       | PORTA.0     | Pin 2            |  
| Light 6       | PORTA.1     | Pin 3            |  
| Light 7       | PORTA.2     | Pin 4            |  

## Documentation  
- [IR_home_source.pdf](IR_home_source.pdf): Main source code and logic breakdown.  
- [[Bill Of Materials IR Remote Home Automation.pdf](https://github.com/An7orAhmed/IR-Remote-Home-Automation-Controller/blob/main/Bill%20Of%20Materials%20IR%20Remote%20Home%20Automation.pdf)]: Hardware components list.  

## Notes  
- Schematics or diagrams referenced in documentation may require adjustments based on hardware revisions.  
- Always verify connections against the microcontroller datasheet.
