# Coral Tile v0.1

Prototype 1

## Design Comprimises

The design of the prototype differs from that of the final design in several ways:

1. No power optomization
    * No / minimal switching converter use
    * No power calculations, just a larger battery
    * Significant power losses from LDO use
2. No custom display
    * LCD elements will be glued to inside of thick plate of glass
3. Use of prebuilt modules
    * Micro Controller
    * Wireless RX
    * Battery PMIC
4. UI Limitations
    * Minimal WiFi UI
    * Charge interruptions can kill wifi
5. Form Factor
   * Emergency debug ports sealed off with removable seal
6. Code
    * Un-optimized, will lack useful functionality



## Experimentation

### GPS
    * Experimentation with GPS to determine viability
### Display
    * Display construction method may be viable alternative to custom lcd
### WiFi
    * Field test for viability of WiFi 
