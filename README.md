# DreamerOS (English below - to be expanded)
Das Betriebssystem zum Schreiben von Geschichten.

WARNUNG: Aktuell besteht die Möglichkeit, dass DreamerOS nicht auf Systemen installiert werden kann, die eine Kapazität unter 500 Gigabyte haben. Dieses Problem wird in Version 1.1 behoben.

Was wird zur Installation benötogt?
2 USB-Sticks
Balena Etcher
Clonezilla
Den img Ordner aus diesem Repository

Was kann es tun?
DreamerOS startet mit Grub und erlaubt dir dich mit dem Display-Manager Ly einzuloggen.
Die voreingestellten Passwörter für root und den User (Dreamer) sind 123456.
Du kannst und solltest beide Passwörter aus Sicherheitsgründen wie folgt ändern:
1. Im Login-Screen drückst du strg+alt+F3
2. Gib "root" ein
3. Gib das Passowrt ein "123456"
4. Gib "passwd Dreamer" ein
5. Gib das neue Passwort für Dreamer ein
6. Gib das neue Passwort für Dreamer erneut ein
7. Gib "passwd" ein
8. Gib das neue Passwort für root ein
9. Gib das neue Passwort für root erneut ein.
Um zum Login zurück zu gelangen drückt ihr strg+alt+F2

Sobald ihr eingeloggt seid startet die Open Source Software Focuswriter. Ihr könnt eure Texte schrieben, sie lokal speichern und mit USB-Sticks, die automatisch erkannt werden ein- und auslagern. 
Ihr findet USB-Sticks im Datei-Explorer Fenster von Focuswriter. 
Die Helligkeit eures Bildschirms kann wie folgt geändert werden:
1. Drückt strg+alt+F3 und loggt euch als Dreamer ein
2. Benutzt den Befehl "light -S (Wert zwischen 0 und 100)" (Beispiel: "light -S 30")

Wie installiert man DreamerOS?
1. Installiert Balena Etcher/Rufus/UnetBootin auf eurem Computer https://etcher.balena.io/
2. Ladet die iso für Clonezilla herunter https://clonezilla.org/downloads.php
3. Folgt den Anweisungen in Balena Etcher um die Clonezilla iso auf den ersten USB Stick zu laden
4. Auf dem zweiten USB Stick fügt ihr den Ordner ein, den ihr hier heruntergeladen habt
5. Bootet vom USB-Stick, den ihr mit Balena Etcher erstellt habt. Die Boot-Folge lässt sich im BIOS eures Computers verändern. Das BIOS öffnet ihr während des Hochfahrens, indem ihr entweder die entf, oder F2 Taste drückt.
6. Im Boot Menü von Clonezilla wählt ihr die Variante mit "Large font & to ram" aus.
7. Schließt den USB-Stick mit dem Ordner von DreamerOS an.
8. Das Keyboard Layout ist egal, ihr könnt den Standard lassen
9. Start Clonezilla
10. Wählt dev to image
11. Wählt localdev
12. Im nächsten Bildschirm sollten bis auf den USB-Stick mit Clonezilla alle Partitionen erscheinen (lokale Festplatte und USB-Stick mit DreamerOS)
13. Drückt strg+C
14. Wählt nun den USB-Stick mit DreamerOS aus
15. Folgt den Schritten für "recover image on local device"

The operating system for writing stories.

DreamerOS version 1.0 is out and ready for grabbing.

WARNING: It is likely that DreamerOS can currently not be installed on devices with a capacity of 500 Gigabytes and below. This problem will be resolved in version 1.1.
Furthermore: DreamerOS is set with a german keyboard layout. A second version to work natively in english is planned.

What can it do?
DreamerOS boots using grub and lets you login with the Ly Display manager.
The preset passwords for both root and user (Dreamer) are 123456.
You can and must change both passwords for security reasons by logging in as root, which you can do as follows:
1. In the login screen, press ctrl+alt+F3.
2. Enter "root"
3. Enter password "123456"
4. Enter "passwd Dreamer"
5. Enter new password for user Dreamer
6. Enter new password again.
7. Enter "passwd"
8. Enter new password for root
9. Enter new password for root again.
To switch back to the login screen press ctrl+alt+F2

Once logged in, the open source Software Focuswriter will start. You can write your novel and save it locally.
USB-Drives will be detected automatically and can be found in the file explorer window provided by Focuswriter.
To change the brightness of your screen, press ctrl+alt+F2, login as Dreamer and use the following command:
light -S "value between 0 and 100" (example: "light -S 30")
