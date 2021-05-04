# How to Bingosync in OBS

### Step 1
Erstelle ein neues Spiel über einen Browser auf bingosync und kopiere die URL
https://bingosync.com

## New Room


### Step 2 
Erstellen eines benutzerdefinierten Docks in OBS  
[Ansicht > Docks > Benutzerdefinierte Browser Docks ]   
- Dockname - Bingo
- URL - {bingosync URL}

### Step 3 (optional)
Erstellen Sie eine Browser-Quelle mit diesen Einstellungen
- URL {bingosync URL}
- Breite 525
- Höhe 475

Benutzerdefiniertes CSS
  
body {
    background-color: rgba(0, 0, 0, 0);
    margin: 0px auto;
    overflow: hidden;
}

.board-container {
    display: inline-block;
    position: fixed;
    width: 100vw;
    top: 0;
    left: 0;
}

.panel-default {
    border-color: rgba(0, 0, 0, 0.6);
    display: none;
}

.popout {
    display: none;
}

!!! Nicht Checken !!!  
- Deaktiveren, wenn Quelle nicht sichtbar 
- Browser bei Szenenaktivierung aktualisieren


**Note**  
Sollte das Fenster leer sein log dich erst via dem Dock in die Session und drücke dann [Cache der aktuellen Seite aktualisieren] in der 'Browser Source'
**Streamlabs OBS** 
Da Slobs Browser cookies nicht teilt muss der login nochmal via overlay gemacht werden. Dannach erst css hinzufügen!

# Rules:

- Kill Cards only count if you survived
- Dogtags only count if found in raid
- Items only count if found in raid