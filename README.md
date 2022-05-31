# tikurl

Kennt ihr diese `https://vm.tiktok.com/?????????/` Links, man weiß gar nicht, womit es sich auf sich hat ... 

In diesem Programm werden wir den Link etwas genauer untersuchen. Hier ist ein Screenshot davon: 

<img width="885" alt="Bildschirmfoto 2022-05-29 um 09 32 42" src="https://user-images.githubusercontent.com/70098046/170857355-c5930a28-5c82-4c9d-9bf1-37d2d754b52f.png">

In dem Bild sehen wir Informationen über den `Autor und dessen ID` . Wir sehen sogar, welche `Sprache` er verwendet. 
Das schlimmste jedoch, wir können sogar sehen, `wer` diesen Link verbreitet hat, über seine ID. Und welche Absicht er hatte, indem Fall über den `Dienst` Whatsapp sollte es geteilt werden auf einem Android `Gerät`.

# Installation

iOS 

`App Store` -> `iSH Shell` -> Jetzt füg ein: 

```
apk add ncurses curl; curl --url https://raw.githubusercontent.com/UnixCro/tikurl/main/tikurl -o /usr/bin/tikurl && chmod +x /usr/bin/tikurl
```

<br>

Android 

`Play Store` -> `Termux` -> Jetzt füg ein: 

```
pkg install ncurses; curl --url https://raw.githubusercontent.com/UnixCro/tikurl/main/tikurl -o $PATH/tikurl && chmod +x $PATH/tikurl
```

<br>

macOS 

Öffne das Terminal -> Jetzt füg ein:

```
osascript -e 'do shell script "sudo mkdir -p /usr/local/bin && sudo /usr/bin/curl --url https://raw.githubusercontent.com/UnixCro/tikurl/main/tikurl -o /usr/local/bin/tikurl && chmod +x /usr/local/bin/tikurl" with administrator privileges'
```

*Das Installationsprogramm wird dich nach einem Passwort fragen. Warum? Aufgrund der Sicherheit in macOS, man braucht höhere Rechte um etwas in /usr/local/bin zu schreiben. Das ist auch gut so. Packet-Manager wie HomeBrew ändern die Schreibrechte. Das Programm ändert überhaupt nichts, es schreibt nur ein neues Programm ins Verzeichnis rein.*


# Hinweise

Falls das Programm ungültige Eingabe erkennt, oder es Netzwerkverbindungsprobleme geben sollte, wird dieses Programm nichts ausfüllen.
Das Programm funktioniert am besten, wenn die Links von Android-Besitzern stammen, da iOS aufgrund seiner Sicherheit, viele dieser Dinge verhindert.

Das Programm bemüht sich stehts, alle Informationen, wie möglich abzurufen. Erwarten Sie aber bitte nicht, dass das Programm zu jeder Zeit Informationen  bereithalten kann. Der Inhalt ist abhängig davon, wie viel TikTok zur Verfügung stellt.

Es ist jedoch sicherlich nicht schlecht, seinen Link zu überprüfen, bevor man ihn weiterschickt.

<br>

Dieses Programm ist derzeit noch in Entwicklung, es ist lange noch nicht perfekt. Falls Sie einen Fehler gefunden haben, melden Sie es hier bitte, um das Programm zu verbessern. 
