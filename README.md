Installationsanleitung
1. Laden Sie Xampp herunter und installieren Sie es.
2. Laden Sie die Java Version 16.0.1 herunter und installieren Sie sie.
3. Fügen Sie die neu heruntergeladene Java Version zu dem System Pfad hinzu.
(Dazu öffnen Sie unter Windows 10 -> Systemumgebungsvariabeln bearbeiten, dann unter Umgebungsvariabeln fügen Sie den Pfad zur Java 16.0.1 bin ordner)
4. Xampp öffnen, neben dem Reiter Mysql auf Config klicken, dann auf my.ini und dann unter max_allowed_packet setzen sie dies auf = 100M
5. Starten Sie den MySQL Server, stellen Sie sicher, dass der Port 3306 für den MySQL Server verwendet wird.
6. Starten Sie den Apache Server, falls Port 80 verwendet wird, dann geben Sie im Browser localhost/phpmyadmin ansonsten geben sie localhost:80/phpmyadmin
7. Unter Phpmyadmin erstellen Sie eine neue Datenbank namens: sep (alles klein geschrieben)
8. Starten Sie die Server.jar (in PowerShell in dem Ordner mit den Jar-Dateien den Befehl „java -jar Server.jar“ eingeben)
9. Starten Sie die Client.jar (in PowerShell in dem Ordner mit den Jar-Dateien den Befehl „java -jar Client.jar“ eingeben)
