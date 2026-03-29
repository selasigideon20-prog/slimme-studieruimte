# Slimme Studieruimte

## Doel
Het doel van dit project is om een slimme studieruimte te maken die automatisch detecteert hoeveel personen aanwezig zijn en de status bepaalt.

## Werking
De ESP32 gebruikt twee IR-sensoren:
- één aan de ingang
- één aan de uitgang

Wanneer iemand binnenkomt, wordt het aantal verhoogd.  
Wanneer iemand buitengaat, wordt het aantal verlaagd.

Op basis van het aantal personen bepaalt het systeem:
- Vrij
- Bezet
- Vol

Daarnaast wordt er een geluidssensor gebruikt.  
Als het te luid wordt, geeft het systeem een waarschuwing met een buzzer.

De status wordt weergegeven op:
- LED’s
- LCD scherm
- Blynk app

## Componenten
- ESP32
- 2x IR sensor
- Geluidssensor
- LCD scherm
- LEDs
- Buzzer
- Drukknop!
- ![WhatsApp Image 2026-03-29 at 10 42 31](https://github.com/user-attachments/assets/e4de7b37-ec70-4873-9778-103c500e85f5)
