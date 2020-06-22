# test
#Dart

Eine Techdemo von Wieser Stefanie im Rahmen der Lehrveranstaltung "Seminar Mobile Software Development" an der FH JOANNEUM. Dieses Techdemo gibt einen ersten Einblick in die Programmiersprache Dart. Behandelt werden Themen wie Installation, erstellen eines Hello World Beispiels und das Kreieren einer kleinen Demoapp.

Dart ist eine Programmiersprache, die hauptsächlich vom Unternehmen Google entwickelt wird. Die erste stabile Version von Dart wurde 2013 veröffentlicht, seitdem wird es laufend weiterentwickelt. Die Sprache wurde als generelle Vielzweck-Programmiersprache entworfen, die insbesondere eine moderne Alternative zu JavaScript zur Verwendung in Webbrowsern darstellen soll. 

Dart-Programme können im Browser, aber auch auf dem Server ausgeführt werden. Das Dart-SDK legt derzeit den Schwerpunkt auf clientseitige Entwicklung. Serverseitige Entwicklung wird beispielsweise mit Bibliotheken wie dart:io unterstützt.

Des Weiteren gibt es noch die Dart-VM. Diese wird für Mobile Apps, serverseitige Programme und als Tool zur Unterstützung der Programmierer weiterentwickelt.

Für den Fall das man Dart erstmal ausprobieren möchte bevor man es herunterlädt, kann man sich bei den folgenden beiden Links durchtesten.

https://dart.dev/#try-dart
oder unter https://dartpad.dartlang.org/

##Installation Windows
Für die Installation von Dart muss Chocolatey installiert sein. Sollte das noch nicht vorhanden sein, so finden Sie die Anleitung dazu ebenfalls auf der Dart Website.
Sobald diese Voraussetzung erfüllt ist, kann nun Dart installiert werden. Dazu braucht man nur dem folgenden Befehl in der Konsole eingeben.

    $ choco install dart-sdk

Sobald dieser Befehl ausgeführt wurde, ist die Installation auch schon abgeschlossen. Die Anleitung zur Installation findet Ihr auf der Dart Website. Der Link dazu ist unten unter dem Punkt Installation abgelegt.

##Installation macOS
Um Dart installieren zu können, muss zuerst Homebrew installiert werden. 

Für die neu Installation muss der nachfolgende Befehl in einem Terminal ausgeführt werden.

    $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Für den Fall das Homebrew bereits installiert wurde, sollten die folgenden Befehle vor der Installation von Dart in einem Terminal ausgeführt werden.

    $ brew update
    $ brew cleanup
    $ brew doctor

Sobald diese Voraussetzung erfüllt ist, kann mit der Installation von Dart begonnen werden.
Jetzt können Sie Dart installieren. Dazu müssen Sie nur die beiden folgenden Befehle ausführen.

    $ brew tap dart-lang/dart
    $ brew install dart

Dies waren die grundsätzlich notwendigen Schritte. Leider habe ich keinen Mac und kann daher die Installation selbst nicht durchführen bzw. überprüfen ob sie funktioniert. Sollten jedoch Fragen bei der Installation auftauchen so kann man unter dem unten hinterlegten Link in der originalen Anleitung nachlesen.

##Hello World

Hier finden sie den Code im Repo.

##Dart Demo Todo - List

In diesem Dart Demo wird als Beispiel eine Todo-Liste implementiert. Dazu wird zuerst ein Projekt Template erzeugt, in dem alle benötigten Ressourcen die die Webapp für das laufen benötigt, erstellt werden.

###Kommandos zum Erstellen eines Projekt Templates.

Schritt eins: sdk installieren

    $ choco install dart-sdk

Schritt zwei: das installieren des webdev Paketes. Dieses Paket dient dazu die selbst entwickelte Webapp zu erstellen, bereitzustellen und zu testen.

    $ pub global activate webdev

Schritt drei: installieren von stagehand (Dart-Projektgenerator).

    $ pub global activate stagehand

Schritt vier: Erstellen eines Ablageordners. 

    $ mkdir quickstart
    $ cd quickstart

Schritt fünf: erstellen des Templats.

    $ stagehand web-simple

Schritt sechs: Einbinden der benötigten Ressourcen.

    $ pub get

letzter Schritt: Starten der localen Webapp auf dem localhost:8080 Port.

    $ Webdev serve

Dies sind alle benötigten Befehle um das Template einzubinden und die erste kleine Webapp zu erstellen. 

Nun muss für unsere Todo – Liste nur noch der spezifische Code hinzugefügt werden. Den finden sie im Ordner ToDoList. 

##Why is Dart cool?

$ Hervorragende Alternative für Javascript basierende Entwicklungen.
$ Entwicklung einer strukturierten, aber auch flexiblen Programmiersprache für das Web.
$ Unterstützung durch Tools, mit deren Hilfe Dart auf allen gängigen Webbrowsern lauffähig ist.
$ Dient als Grundlage für Flutter, und somit für die Mobile App Entwicklung bestens geeignet.

##Quellen und weiterführende Links

Installationsanleitung für Windows und Mac:
https://dart.dev/get-dart

Dart im Browser:
https://dart.dev/#try-dart
https://dartpad.dartlang.org/

Tutorials:
https://www.tutorialspoint.com/dart_programming/dart_programming_quick_guide.htm
https://dart.dev/tutorials/web/get-started
https://dart.dev/samples


