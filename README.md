# Finalfinalcode

#include <kipr/botball.h>
#include "Alexandria.h"

int main()
{//Begin int
    //Slapper()
    Vroom(100,100,1400);
      //Moves towards black line
    Raven(2000,3350);
      //Should follow straight through until parallel with red cubes
    Vroom(0,100,1500);
      //MOves left
    Vroom(100,0,1500);
      //MOve right to face red cubes
    Vroom(100,100,1500);
      //Robot has pushed red blocks to square
      //The robot will now trek to the red blocks
    Vroom(0,-100,1500);
      //Robot has turned left backwards
    Vroom(-100,-100,1500);
      //Robot has moved backwards
    Vroom(-100,0,1500);
      //Robot has turned right backwards
    Vroom(0,100,1500);
      //Robot has turned left backwards
    Vroom(-100,-100,1500);
      //Robot has walked backwards
    Vroom(0,-100,1500);
      //Robot has turned left backwards
    Vroom(-100,-100,-1500);
      //Backwards
    Vroom(100,-100,1500);
      //RObot is now facing the green blocks
    Vroom(100,100,1500); 
      //Robot has now pushed the blocks
    Vroom(-100,-100,1500);
    printf("Robot is now back in first position further actions are incouraged\n");           
    //Task 2
    Vroom(100,0,1500);
      //Robot facing tubes thingy
    Vroom(100,100,1500);
      //Im(go down a bit)
      //Robot has to have collected three poms
    Vroom(-100,-100,1500);
      //Robot has walked backwards
    Vroom(100,0,1500);
      //Robot has turned right
    Vroom(100,100,1500);
      //Robot has walked forward a bit
    Vroom(0,100,1500);
      //Robot has turned left
    Vroom(100,100,1500);
      //Robot is now in front of second set of pom poms, claw should have collected the thingies
    return 0; 
}//End int
