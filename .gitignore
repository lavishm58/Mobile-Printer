#include <Servo.h>

Servo myservo;
Servo myservo1;
Servo myservo2;
Servo myservo3;

int x=360; int flag=0; int i; int j;
char letter; 
void Xplus() {
   myservo.write(90);
   myservo2.write(90);
   myservo1.write(x);
   myservo3.write(-x);
  }
void Xminus() {
   myservo.write(90);
   myservo2.write(90);
   myservo1.write(-x);
   myservo3.write(x);
  }  
void Yplus() {
   myservo.write(-x);
   myservo2.write(x);
   myservo1.write(90);
   myservo3.write(90);
  } 
void Yminus() {
   myservo.write(x);
   myservo2.write(-x);
   myservo1.write(90);
   myservo3.write(90);   
  }  
void Zplus() {
   myservo.write(-x);
   myservo2.write(x);
   myservo1.write(x);
   myservo3.write(-x);
  }
void Zminus() {
   myservo.write(x);
   myservo2.write(-x);
   myservo1.write(-x);
   myservo3.write(x);
  }
void Wplus() {
   myservo.write(-x);
   myservo2.write(x);
   myservo1.write(-x);
   myservo3.write(x);
  }
void Wminus() {
   myservo.write(x);
   myservo2.write(-x);
   myservo1.write(x);
   myservo3.write(-x);
  }
void semi() {
      for(i=0;i<3;i++)
      {
        myservo.write(360);
        myservo1.write(360);
        myservo2.write(360);
        myservo3.write(360);
        delay(1200);
    }
  }
void semireverse() {
        for(i=0;i<3;i++)
      {
          myservo.write(-360);
        myservo1.write(-360);
        myservo2.write(-360);
        myservo3.write(-360);
        delay(1200);
      }
  }     
void starting() {
  myservo.attach(22);
  myservo1.attach(24);
  myservo2.attach(26);
  myservo3.attach(28);  
  }  
void stopping() {
  myservo.detach();
  myservo1.detach();
  myservo2.detach();
  myservo3.detach();
  }          

void setup() {
  Serial.begin(9600);
}
void loop(){
    Serial.println("Enter the letter to be printed");
    if (Serial.available())
    {
      letter = Serial.read();
      flag = 0;
    }

   if(flag==0)
   {

      
    if(letter == 'a')
      {
        starting();
        Serial.println("You have entered A");
        Zplus();
        delay(1000);
        Wminus();
        delay(1000);
        Wplus();
        delay(500);
        Xminus();
        delay(800);
        stopping();
        Serial.println("Mission Completed");
       }

      
         else if(letter == 'b')
         {
          starting();
          Serial.println("You have entered B");
          Yplus();
          delay(1000);
          Xplus();
          delay(500);
          Yminus();
          delay(500);
          Xminus();
          delay(500);
          Xplus();
          delay(500);
          Yminus();
          delay(500);
          Xminus();
          delay(500);
          stopping();          
          Serial.println("Mission Completed");                                
          }

          
         else if(letter == 'c')
         {
          starting();
          Serial.println("You have entered C");
          semi(); 
          stopping();          
          Serial.println("Mission Completed");            
          }

          
         else if(letter == 'd')
         {
          starting();
          Serial.println("You have entered D");
          myservo.write(90);
          myservo2.write(-360);
          myservo3.write(90);
          myservo1.write(-360);
          delay(5000);
          Yplus();
          delay(1000);
          stopping();          
          Serial.println("Mission Completed");                     
          }

                                    
     else if(letter == 'e')
      {
        starting();
        Serial.println("You have entered E");
        Xplus();
        delay(500);
        Xminus();
        delay(500);
        Yplus();
        delay(500);
        Xplus();
        delay(500);
        Xminus();
        delay(500);
        Yminus();
        delay(1000);
        Xplus();
        delay(500);
        stopping();
        Serial.println("Mission Completed");
        }

         
      else if(letter == 'f')
      {
        starting();
        Serial.println("You have entered F");
        Xplus();
        delay(500);
        Xminus();
        delay(500);
        Yplus();
        delay(500);
        Xplus();
        delay(500);
        Xminus();
        delay(500);
        Yminus();
        delay(1000);
        stopping();
        Serial.println("Mission Completed");                
        }

        
         else if(letter == 'g')
         {
          starting();
          Serial.println("You have entered G");
          semi();
          delay(1000);
          Wminus();
          delay(500);
          Zplus();
          delay(450);
          Zminus();
          delay(900);
          Wplus();
          delay(500);
          stopping();          
          Serial.println("Mission Completed");            
          }

                  
       else if(letter == 'h')
       {
        starting();
        Serial.println("You have entered H");
        Xplus();
        delay(500);
        Yplus();
        delay(500);
        Yminus();
        delay(1000);
        Yplus();
        delay(500);
        Xminus();
        delay(500);
        Yplus();
        delay(500);
        Yminus();
        delay(1000);
        stopping();
        Serial.println("Mission Completed");        
        }

        
       else if(letter == 'i')
       {
        starting();
        Serial.println("You have entered I");
        Xplus();
        delay(1000);
        Xminus();
        delay(500);
        Yplus();
        delay(1000);
        Xminus();
        delay(500);
        Xplus();
        delay(1000);
        stopping();
        Serial.println("Mission Completed");   
        }

        
         else if(letter == 'j')
         {
          starting();
          Serial.println("You have entered J");
          Xplus();
          delay(1000);
          Xminus();
          delay(500);
          Yminus();
          delay(1000);
          Xminus();
          delay(500);
          stopping();          
          Serial.println("Mission Completed");                     
          }

                  
       else if(letter == 'k')
       {
        starting();
        Serial.println("You have entered K");
        Zplus();
        delay(500);
        Zminus();
        delay(500);
        Wminus();
        delay(500);
        Wplus();
        delay(500);
        Yplus();
        delay(500);
        Yminus();
        delay(1000);
        stopping();
        Serial.println("Mission Completed");
        }

        
        else if(letter == 'l')
        {
          starting();
          Serial.println("You have entered L");
          Yminus();
          delay(1000);
          Xplus();
          delay(750);
          stopping();
          Serial.println("Mission Completed");
          }

          
         else if(letter == 'm')
         {
          starting();
          Serial.println("You have entered M");
          Yplus();
          delay(1000);
          Wminus();
          delay(500);
          Zplus();
          delay(500);
          Yminus();
          delay(1000);
          stopping();
          Serial.println("Mission Completed");                    
          }

          
         else if(letter == 'n')
         {
          starting();
          Serial.println("You have entered N");          
          Yplus();
          delay(1000);
          Wminus();
          delay(1120);
          Yplus();
          delay(1000);
          stopping();
          Serial.println("Mission Completed");                    
          }

          
         else if(letter == 'o')
         {
          starting();
          Serial.println("You have entered O");
          semi();
          semi();
          stopping();          
          Serial.println("Mission Completed");                      
          }
          

         else if(letter == 'p')
         {
          starting();
          Serial.println("You have entered P");
          Yplus();
          delay(3000);
          semi();
          semi();
          stopping();          
          Serial.println("Mission Completed");            
          }

          
         else if(letter == 'q')
         {
          starting();
          Serial.println("You have entered Q");

           semi();
           semi();
           delay(500);
           Yplus();
           delay(1000);
           stopping();          
           Serial.println("Mission Completed");           
          }

          
         else if(letter == 'r')
         {
          starting();
          Serial.println("You have entered R");
          Yplus();
          delay(1000);
          Xplus();
          delay(500);
          Yminus();
          delay(500);
          Xminus();
          delay(500);
          Wminus();
          delay(750);
          stopping();          
          Serial.println("Mission Completed");          
         }
         

         else if(letter == 's')
         {
          starting();
          Serial.println("You have entered S");
          myservo.write(90);
          myservo2.write(360);
          myservo3.write(90);
          myservo1.write(360);
          delay(9000);
          semireverse();
          stopping();          
          Serial.println("Mission Completed");          
          }

                                                  
         else if(letter == 't')
         {
          starting();
          Serial.println("You have entered T");
          Yplus();
          delay(1000);
          Xplus();
          delay(500);
          Xminus();
          delay(1000);
          stopping();
          Serial.println("Mission Completed");                               
          }

          
         else if(letter == 'u')
         {
          starting();
          Serial.println("You have entered U");
          Yminus();
          delay(1000);
          semi();
          Yminus();
          delay(1000);
          stopping();          
          Serial.println("Mission Completed");                      
          }

                    
         else if(letter == 'v')
         {
          starting();
          Serial.println("You have entered V");          
          Wminus();
          delay(1000);
          Zplus();
          delay(1000);
          stopping();
          Serial.println("Mission Completed");            
          }

          
         else if(letter == 'w')
         {
          starting();
          Serial.println("You have entered W");          
          Wminus();
          delay(1000);
          Zplus();
          delay(1000);
       
          Wminus();
          delay(1000);
          Zplus();
          delay(1000);
          stopping();          
          Serial.println("Mission Completed");           
          }

          
         else if(letter == 'x')
         {
          starting();
          Serial.println("You have entered X");           
          Wminus();
          delay(1000);
          Wplus();
          delay(500);
          Zplus();
          delay(500);
          Zminus();
          delay(1000);
          stopping();          
          Serial.println("Mission Completed");           
          }

          
         else if(letter == 'y')
         {
          starting();
          Serial.println("You have entered Y");           
          Zplus();
          delay(1200);
          Zminus();
          delay(500);
          Wplus();
          delay(500);
          stopping();          
          Serial.println("Mission Completed");            
          }

          
         else if(letter == 'z') 
         {
          starting();
          Serial.println("You have entered Z");
          Xplus();
          delay(1000);
          Zminus();
          delay(1250);
          Xplus();
          delay(1000);
          stopping();          
          Serial.println("Mission Completed");                    
          }
                             
    flag=1; 
    }
      
 }
