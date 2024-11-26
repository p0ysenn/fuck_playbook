# fuck_playbook
no excuse not to learn utility

<!-- TextPositionOffset = [ 
    Distance to Player (value < 0 = closer), 
    Left/Right (value > 0 = right), 
    Height (value > 0 = higher)] -->

## Download:
Oben rechts auf den "Code" Button klicken und das Repository als ZIP runterladen

## Installation:
Den ZIP Ordner entpacken und den Inhalt des "fuck_playbook-master" Ordners unter diesem Pfad einfügen<br>
    *common\Counter-Strike Global Offensive\game\csgo\annotations*<br>
Sollte der *annotations* Ordner noch nicht existieren, muss man ihn selber anlegen.<br>
<br>
Der Inhalt des Ordners sollte dann so aussehen:
csgo
│   ├───annotations\
│   │   ├───ancient\
│   │   ├───anubis\
│   │   ├───dust\
│   │   ├───inferno\
│   │   ├───mirage\
│   │   ├───nuke\
│   │   ├───overpass\
│   │   ├───train\
│   │   └───vertigo\

## Vorraussetzungen für die Verwendung:<br>
 - sv_cheats true
 - sv_allow_annotations true


## Verwendung:
Ingame wird das ganze mit dem Console Command: "*annotation_load &lt;mapname&gt;/&lt;filename&gt;*" geladen.<br><br>

*&lt;mapname&gt;* gibt den Namen der gewünschten map an (z.B. "anubis")<br>
*&lt;filename&gt;* gibt den Name des Lineup Sets an das man laden will (Standart ist wieder der Map Name)
<br>
<br>
Beispiel:<br>
annotation_load anubis/anubis
