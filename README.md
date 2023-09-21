# Technique de détection laser

## Laser Arduino



### code nécessaire 


 #define LaserIn   4
 
 #define LaserOut  5

 bool EtatInt=false;`

 void setup() {
  pinMode(LaserIn, INPUT);
  pinMode(LaserOut, OUTPUT);
} 

>void loop() {
  EtatInt=digitalRead(LaserIn);
 cdigitalWrite(LaserOut,EtatInt);
} 
![image laser Arduino](assets/images/Diode-laser.png)

































#### référence
- [Site Arduino Pointeur laser Arduino](https://www.electronique-mixte.fr/projet-pointeur-laser-avec-arduino/)
