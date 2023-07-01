# EmpyrionModPackage
Das Paket aller meiner Mods 

## Nitrado (und ggf andere Gamehoster)
Gamehoster nutzen oft eine "Whitelist" der erlaubten Prozessnamen (z.B. EmpyrionPlayfieldServer.exe), daher musst man für diese den Hostprozess 
umbenennen.
Hierfür bitte die "...\ModLoader\Client\Configuration.xml" Datei wie folgt ändern
```
<Configuration xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <PathToModHost>..\Host\EmpyrionModHost.exe</PathToModHost>
  <AutostartModHost>true</AutostartModHost>
```
in
```
<Configuration xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <PathToModHost>..\Host\EmpyrionPlayfieldServer.exe</PathToModHost>
  <AutostartModHost>true</AutostartModHost>
```
und die Datei "...\ModLoader\Host\EmpyrionModHost.exe.bin" in "...\ModLoader\Host\EmpyrionPlayfieldServer.exe.bin"
umbenennen bzw falls die ".bin" Datei nicht existiert die Datei "...\ModLoader\Host\EmpyrionModHost.exe" in "...\ModLoader\Host\EmpyrionPlayfieldServer.exe.bin"

# English version

# EmpyrionModPackage
All my running mods with the ModLoader 

## Nitrado (and possibly other gamehosters)
Gamehosts often use a "whitelist" of allowed process names (e.g. EmpyrionPlayfieldServer.exe), so you have to rename the host process for them. 
rename the host process.
To do this, please change the "...\ModLoader\Client\Configuration.xml" file as follows
```
<Configuration xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <PathToModHost>..\Host\EmpyrionModHost.exe</PathToModHost>
  <AutostartModHost>true</autostartModHost>.
```
in
```
<Configuration xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <PathToModHost>..\Host\EmpyrionPlayfieldServer.exe</PathToModHost>
  <AutostartModHost>true</autostartModHost>.
```
and rename the file "...\ModLoader\Host\EmpyrionModHost.exe.bin" to "...\ModLoader\Host\EmpyrionPlayfieldServer.exe.bin".
rename or if the ".bin" file does not exist rename the file "...\ModLoader\Host\EmpyrionModHost.exe" to "...\ModLoader\Host\EmpyrionPlayfieldServer.exe.bin".
