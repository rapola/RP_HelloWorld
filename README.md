## Useful links:

### ASCII
https://www.ascii-codes.com/

### Github emojis
https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md
### Github table
https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/
- - - -
### ESP32
* SPIFFS
  * https://forum.m5stack.com/topic/1590/esp32-and-the-spiffs-file-system <br>
  * https://diyprojects.io/esp32-get-started-spiff-library-read-write-modify-files <br>
  * http://www.getmicros.net/esp8266-spiffs-example.php <br>
- - -
### AVR
* TIMER
  * https://www.arduinoslovakia.eu/application/timer-calculator
* New AVR 0 and 1 Series
  * https://hackaday.io/project/165881-attiny-1-series-with-arduino-support/log/164411-new-method-for-writting-registers-on-the-0-and-1-series

- - - -
### C/C++ bitmanipulation macros
* Put this macros in top of a header file...
* Set a bit:
  * #define SET_BIT(byte, bit) ((byte) |= (1UL << (bit)))

* Clear a bit:
  * #define CLEAR_BIT(byte,bit) ((byte) &= ~(1UL << (bit)))

* Toggle a bit:
  * #define TOGGLE_BIT(byte, bit) ((byte) ^= (1UL << (bit)))

* Returns true if specific bit is set
  * #define IS_SET(byte,bit) (((byte) & (1UL << (bit))) >> (bit))
 
* See (06.06.2023):
  * https://www.codementor.io/@hbendali/c-c-macro-bit-operations-ztrat0et6

- - -
## todo
- make a repo for defined pinouts of often used connectors
- make a countdown library for arduino
