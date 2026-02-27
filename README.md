# lineFollower.Main

Iată o descriere profesională a proiectului, structurată special pentru a evidenția competențele tehnice în fața unui recrutor:

### **Robot Autonom Line Follower**

**Descriere Generală:**
Dezvoltarea unui sistem embedded autonom capabil să identifice și să urmărească un traseu marcat printr-o linie neagră, utilizând platforma Arduino. Proiectul integrează controlul motoarelor de curent continuu cu procesarea semnalelor de la senzori analogici pentru a asigura o navigare precisă în timp real.

**Responsabilități și Realizări Tehnice:**

* **Integrarea și Calibrarea Senzorilor:** Implementarea unui subsistem de achiziție de date utilizând biblioteca **QTRSensors** pentru doi senzori analogici. Am dezvoltat o rutină de calibrare automată (400 de iterații) pentru a asigura adaptabilitatea robotului la diverse condiții de iluminare și contrast.
* **Algoritm de Control și Navigație:** Proiectarea unei logici de decizie care interpretează valorile senzorilor (pe o scară de la 0 la 1000) pentru a determina direcția optimă de deplasare: înainte, stânga sau dreapta.
* **Controlul Motoarelor (PWM):** Gestionarea sistemului de propulsie prin semnale **PWM (Pulse Width Modulation)** pentru controlul vitezei, permițând tranziții line între mersul înainte și manevrele de virare.
* **Sistem de Diagnoză și Feedback:** Implementarea unei interfețe de debugging prin comunicare Serială și feedback vizual prin LED-uri pentru monitorizarea stării senzorilor și a direcției de mișcare în timpul testării.
* **Eficientizarea Codului:** Utilizarea tipurilor de date enumerate (`enum`) și structurarea modulară a funcțiilor pentru a asigura un cod lizibil și ușor de întreținut.

**Tehnologii Utilizate:**

* **Limbaj:** C++ (Arduino Sketch).
* **Hardware:** Microcontroler compatibil Arduino, senzori analogici QTR, drivere de motor DC, LED-uri de stare.
* **Concepte:** Control în buclă deschisă, procesare de semnal, sisteme de timp real, calibrare senzori.
