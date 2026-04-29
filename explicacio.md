Has d'anar al editor de registros de Windows
Ho pots fer posant `regedit` a la terminal

Un cop alla vas a HKEY_LOCAL_MACHINE a SOFTWARE a Microsoft a Command Processor
Fas un nou valor: Right click -> New String value, l'anomenes "Autorun"-> Right Click on the string value and click on Modify
Poses:

DOSKEY /MACROFILE="path\to\macro\file"

Aquesta macro file per exemple jo la he posat a dins de C:\bat\ perque si, de fet el directory bat l'he creat jo
i li he dit macros.doskey perue si, pero li podria dir com volgués i posar-li una altra extensió

i sino es pot editar el lloc del shortcut to cmd.exe mirant això
<https://kunalspathak.github.io/2020-11-21-About-doskeys/>
per la part del final a l'apartat **Workflow**
