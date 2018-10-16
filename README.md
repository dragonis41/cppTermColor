# cppTermColor
with with simple librairie you can make colored text in a terminal in c++

example:


    #include <iostream>
    #include "color.h"
      
    int main()
    {
      //this code will display " hello" in red, " it's me" in light green and background in blue
      printf("%s hello%s it\'s me%s\n", RED, LGREEN, BGBLUE);
    }
     
 or
    
    int main()
    {
      //this code is used to display the text "HELLO" blinking in red with black background
      printf("%s%s HELLO %s\n", BLINK, RED, BGBLACK);
    }

