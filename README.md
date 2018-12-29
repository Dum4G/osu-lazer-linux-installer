# News
## 29.12.2018
A new Stable-and-or-Daily-Build-System, for more info check out the Wiki link
https://github.com/Alexmitter/osu-lazer-linux-installer/wiki/Stable-and-or-Daily-Build-System


A new Dependency Installing Process is now included, the Ubuntu 18.04 Script should be the base for porting it to other distros.
Ports are welcome as a Pull Request, name the folder and script as i gave the example with ubuntu18.04.

I tested the script on a brand new Virtual Machine and i was able to make it a one click install. No problems what so ever. But apart from that, the script is untested. If you have any issues with it, please make a issue.




# osu-lazer-linux-installer ENGLISH

osu!lazer is the new early development open source version of osu!

This script helps you build, maintain and play on the latest build without any stress on your favorite Linux distribution.

## Instructions (for Ubuntu/Debian)

- Install .NET Core SDK 2.2: https://dotnet.microsoft.com/download
- Install dependencies: 
`sudo apt install git dialog libglfw3-dev libgles2-mesa-dev`
- Clone this repository: 
`git clone https://github.com/Alexmitter/osu-lazer-linux-installer.git`
- Go to the osu-lazer-linux-installer directory (`cd osu-lazer-linux-installer`) and run the script: 
`./start.sh`
- Choose your language and then pick the "Clone and Compile osu!lazer" option - the installation will now begin
- Enjoy!

Have fun playing the game. If any issues appear, please submit an issue.

# osu-lazer-linux-installer ITALIANO (OUTDATED - needs a mention about .NET Core 2.2 being a requirement)

osu!lazer è la nuova versione bleading-edge di osu!
Questo script ti aiuterà a costruire, mantenere aggiornato e giocare sempre alla versione più aggiornata di Osu senza stress sulla tua distro preferita.


Le Dipendenze sono: dotnet core sdk (provato con la versione 2.1.4), dialog, libglfw3-dev, libgles2-mesa-dev, libgbm-dev.

Scarica dotnet core sdk da https://www.microsoft.com/net/download

Avvia "bash start.sh" per eseguire il programma

Passo 1: Avvia la clonazione e la compilazione, Poi passa all'installazione delle dipendenze

Passo 2: Dotnet 2.1 (Un Placeholder, per ora installabile manualmente)

Passo 3: Installa le Dipendenze comuni nelle distro Ubuntu/Debian che servono per l'avvio corretto di osu!lazer

Passo 4: Installa le librerie Bass dalla cartella di compilazione di osu (Prima di ciò, si deve completare il primo passo) (Anche questo per ora è un PlaceHolder, segui il tutorial in "Fix OpenTK Issue.txt")

Divertiti giocando a osu! Se dovrebbe apparire un errore o bug. Facci sapere tramite la sezioni Errori di Github.

# osu-lazer-linux-installer POLSKI (OUTDATED - needs a mention about .NET Core 2.2 being a requirement)

osu!lazer jest najnowsza wersja osu!
Ten skrypt pomoże ci budować, zaktualizować i zawsze grać w najnowszą wersję Osu bez stresu na twoich ulubionych dystrybucjah linux.

Wymagane pakiety to: dotnet core sdk (wypróbowane z 2.1.4), dialog, libglfw3-dev, libgles2-mesa-dev, libgbm-dev.

pobierz dotnet core sdk z https://www.microsoft.com/net/download

otwórz "bash start.sh" to execute the tool

Opcja 1: Sklonuj i Skompiluj, później zainstaluj wymagane pakiety

Opcja 2: Dotnet 2.1 (na razie możliwe tylko manualnie)

Opcja 3: Zainstaluj wspólne zależności do dystrybucji na Debianie/Ubuntu, które są wymagane przez osu!lazer

Do 4: Zainstaluj biblioteki bass z folderu komiplacji osu (Tylko po wykonaniu pierwszej opcji) (To jest Placeholder, na razie zajrzyj do "Fix OpenTK Issue.txt")

Baw się dobrze grając w OSU, jeśli znajdziesz jakiś problem, daj nam znać na githubie w zakładce problemów.

# osu-lazer-linux-installer GERMAN

osu!lazer ist die neue frühe Open-Source-Version von osu!

Dieses Skript hilft Ihnen bei der Erstellung, Wartung und Wiedergabe des neuesten Builds, ohne für Sie einen großen aufwand darzustellen.

## Anweisungen (für Ubuntu/Debian)

- Installieren Sie das.NET Core SDK 2.2: https://dotnet.microsoft.com/download
- Abhängigkeiten installieren: 
`sudo apt install git dialog libglfw3-dev libgles2-mesa-dev`
- Klonen Sie dieses Repository: 
`git clone https://github.com/Alexmitter/osu-lazer-linux-installer.git`
- Gehen Sie in das Verzeichnis osu-lazer-linux-installer (`cd osu-lazer-linux-installer`) und führen Sie das Skript aus: 
`./start.sh`
- Wählen Sie Ihre Sprache und dann die Option "Klonen und Kompilieren osu!lazer" - dann beginnt dann auch schon die Installation.

- Führen Sie das Skript erneut aus (`./start.sh`) und wählen Sie "Run osu!lazer", um das Spiel zu starten.

Viel Spaß beim Spielen. Wenn Probleme auftreten, reichen Sie bitte ein sog. [issue](https://github.com/Alexmitter/osu-lazer-linux-installer/issues/new) ein.
