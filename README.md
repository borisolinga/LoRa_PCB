# LoRa-Sender PCB

Die Leiterplatte (PCB) des LoRa-Senders deckt alle für dieses Projekt erforderlichen Funktionen ab. Das Design des Schaltplans und der Platinenlayouts wurde mit der EDA-Software (Electronic Design Automation) **Autodesk EAGLE** entwickelt.

## Eigenschaften der Leiterplatte

Die Leiterplatte bietet folgende Hauptfunktionen:

- **LoRa-Datenübertragung:** Das Board ermöglicht eine zuverlässige Kommunikation über LoRa.
- **Status-LED:** Eine LED zeigt durch Blinken an, wenn ein Paket erfolgreich gesendet wurde.
- **Serielle Schnittstelle:** Eine UART/USB-Schnittstelle ermöglicht die Kommunikation mit einem Computer.
- **Mikrocontroller:**  
  - **ATmega328P**, der aufgrund seiner Kompatibilität mit Arduino-Entwicklungsboards ausgewählt wurde.  
 
- **Stromverbrauchsmessung:**  
  - Zwei Jumper sind zur Stromverbrauchsanalyse vorgesehen:  
    1. Für das LoRa-Modul.  
    2. Für das Gesamtsystem.
  - Ein zusätzlicher Jumper ermöglicht die Nutzung einer externen Stromversorgung.

## Projektinhalt

- **Schaltplan:** Enthält das vollständige PCB-Design in Autodesk EAGLE.
- **Stückliste (BOM):** Eine vollständige Liste der verwendeten Komponenten.


## Nutzung

1. **Repository klonen:**

   ```bash
   git clone https://github.com/borisolinga/LoRa_Transmitter_PCB.git
   cd LoRa_Transmitter_PCB
