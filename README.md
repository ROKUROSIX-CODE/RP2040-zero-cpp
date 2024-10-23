/* Programa en ARDUINO IDE con C++, simple en tu RP2040 zero de Aliexpress.

  +Segurate de tener Istalado los repocitorios:+

  https://github.com/adafruit/Adafruit-GFX-Library
  https://github.com/adafruit/Adafruit_SSD1306

-----------------------------------------------------------------------------------
                            *IMPORTANTE*

  Abre la Libreria Adafruit_SSD1306 en C++ y editala con un Editor C++.
  C:\Users\TuNombreDeUsuario\Documents\Arduino\libraries\Adafruit_SSD1306
  Abre el Documento Adafruit_SSD1306.cpp

  Busca la linea:
  41|
  42| #include <pgmspace.h>
  43|

  Y "comentala"; Debería de quedar así:

  41|
  42| //#include <pgmspace.h>
  43|

  Si no haces esto no funcionará y te mostrará esa misma librería como "error".

                    *AQUÍ TERMINA LO IMPORTANTE*
-----------------------------------------------------------------------------------

  Este programa utiliza los "PIN" "Predeterminados" proporcionados por Arduino IDE.
            
          -----____-----
        5V|   |    |   |0
       GND|    ----    |1
       3V3|            |2
        29|            |3
        28|            |4 <---- GP4  SDA
        27|            |5 <---- GP5  SCL
        26|            |6
        15|            |7
        14|            |8
          --------------
           13 12 11 10 9
    RP2040 zero 2MB (Aliexpress)


    Este programa es para una pantalla 128x64 pixeles Blanca.
               3V3
           GND /5V GP4 GP5
            |   |   |   |
            |   |   |   |
            V   V   V   V

           GND VCC SCL SDA
          -----------------
          |*   . . . .    *|
          |   ----------   |
          |  |          |  |
          |  |          |  |
          |   ----------   |
          -*--------------*-
         OLED 128x64 3,3 V-5V 
         MonoCromatica, Blanco

Espero que más gente pueda Aprender con el RP2040 y C++,
hice esto porque no encontré ningun tutorial al respecto.

Porque Jehová(Yahweh) da la sabiduría, Y de su boca viene el conocimiento y la inteligencia. —Proverbios 2:6. */
