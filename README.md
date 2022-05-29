# tikurl

Kennt ihr diese `https://vm.tiktok.com/?????????/` Links, man weiß gar nicht, was es mit sich auf sich hat.

In diesem Programm werden wir den Link etwas genauer untersuchen: 

<img width="885" alt="Bildschirmfoto 2022-05-29 um 09 32 42" src="https://user-images.githubusercontent.com/70098046/170857355-c5930a28-5c82-4c9d-9bf1-37d2d754b52f.png">

In dem Bild sehen wir Informationen über den `Autor und dessen ID` . Wir sehen sogar, welche `Sprache`er verwendet. 
Das schlimmste jedoch, wir können sogar sehen, `wer` diesen Link verbreitet hat, über seine ID. Und welche Absicht er hatte, indem Fall über den `Dienst` Whatsapp sollte es geteilt werden auf einem Android `Gerät`.

# Hinweis

Falls das Programm ungültige Eingabe, oder es Netzwerkverbindungsprobleme geben sollte, wird dieses Programm nichts ausfüllen.
Das Programm funktioniert am besten, wenn die Links von Android-Besitzern stammen, da iOS aufgrund seiner Sicherheit, viele dieser Dinge verhindert.


# Installation

iOS 

`App Store` -> `iSH Shell` -> Jetzt gib ein: `curl --url $INPUT -o /usr/bin/tikurl` 

<br>

Android 

`Play Store` -> `Termux` -> Jetzt gib ein: `curl --url $INPUT -o $PATH/tikurl` 

macOS 

Öffne das Terminal -> `osascript -e 'do shell script "sudo /usr/bin/curl --url $INPUT -o /usr/local/bin/tikurl" with administrator privileges'`

