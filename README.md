# SWE-MehrMarkt


## Notwendigkeiten

Docker muss installiert sein. Folgen Sie zum installieren dem untenstehen Link https://www.docker.com/products/docker-desktop/
Gegebenenfalls ist es notwendig, die Endung der heruntergeladenen Datei auf
„.exe“ zu ändern.

Docker ist erfolgreich installiert, wenn man diesen Befehl als Admin auf der Konsole

"docker --version"

problemlos im Terminal ausführen kann.
Bei Problemen finden Sie weitere Infos unter https://docs.docker.com/get-docker/"

## Die Ausführung des Systems

1.	SWE-Mehrmarkt.zip auf dem Desktop entpacken
2.	Die Konsole als Systemadmin öffnen.
3.	Docker starten. Dazu an den Standartmäßig angezeigten Pfad WINDOWS\system32>
noch den Pfad zur Datei „Docker Desktop.exe“ anfügen.

start "Docker" "C:\Programme\Docker\Docker\Docker Desktop.exe"

Falls die Datei auf Ihrem Rechner woanders liegt, den Pfad gegebenenfalls anpassen.

4.	In der Konsole in den Ordner „SWE-Mehrmarkt“ navigieren. Standartmäßig sollte man dazu den Kommandos des folgenden Bildes folgen können. Falls der Ordner von Ihnen woanders abgelegt wurde, muss der Pfad angepasst werden.
 
5.	Wenn Sie sich mit der Konsole im Ordern „SWE-Mehrmarkt“ befinden. Folgenden Befehl ausführen:

docker compose up -–build

6.	Den Localhost öffnen. Das Dashboard des Projektes ist hier nun sichtbar.

C:\Users\User>cd Desktop

C:\Uscrs\User\Desktop>cd	SWE Mehrmarkt

C:\Users\User\Desktop\SWE Mehrmarkt>docker compose

[ +] Building 1.8s	(34135)

=> [swe-rehrrarkt-back-end internal]	for doc<er.io/library/openjdk:19-slim-buster	1.  7s


# Mögliche Probleme beim Compilieren:
Sollten Sie auf die folgende Fehlermeldung stoßen

```
/bin/sh: 1: ./mvnw: not found
```

Ist die unter dem folgenden Link zu findende Lösung anzuwenden:
https://stackoverflow.com/questions/61226664/build-docker-error-bin-sh-1-mvnw- not-found
