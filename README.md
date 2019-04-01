# Home assistant

### Forside
![](doc/images/home_assistant_main.png)

### Oversikt over områder ute
![](doc/images/home_assistant_outside.png)

### Oversikt over rom inne
![](doc/images/home_assistant_inside.png)

### Stemning
Kortet for soverommet og stua er satt opp med vertical-stack. Øvre del inneholder
et customoppsett for valg av scener/stemning.

![](doc/images/home_assistant_scene_vertical-stack.png) 

Et annet eksempel på scene/stemningskort

![](doc/images/home_assistant_scene_card.png)

#### Flyt på scenevalg/scenevalg
1. Entity på kort er en switch
2. Switch trigger en automatisering
3. Automatiseringen har to funksjoner
   1. Et sett med input-booleans oppdateres slik at ikonene på kortet markeres riktig
   2. Skrur på valgt scene/stemning
4. Scene endrer lysene 

### System
Støtter home-assistant [v0.90.2](https://github.com/home-assistant/home-assistant/releases/tag/0.90.2)