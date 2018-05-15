# Git Nutzung

## Download

Git kann in einer einfachen, Portablen version [**hier**](https://github.com/git-for-windows/git/releases/download/v2.17.0.windows.1/PortableGit-2.17.0-32-bit.7z.exe) heruntergeladen werden. Dies bringt eine einfache Konsole mit, die geöffnet werden kann und in welcher man git benutzen kann.

## Nutzung

Wollen wir eine Repository clonen, so kann man dies in der Konsole mit folgenden Command machen:

```
git clone git@github.com:itf17b/<nameDerRepo>
```

Nun wurde ein Ordner mit gleichen namen erstellt wie der der Repo, welchen wir folgendermaßen betreten können:

```
cd <nameDerRepo>
```

Man sollte **jedes mal**, bevor man Änderungen an der Repo vornehmen will erstmal alle bis jetzt eingegangenen Veränderungen pullen mit:
```
git pull
```

Werden nun Änderungen an Dateien der Repo vorgenommen, so kann man diese anschließend committen:

```
git add .
git commit -m "[<Nametag>] <commit message>"
git push
```

Nun wird die Eingabe des Password benötigt, außer man hat seinen Private Key bei GitHub hinterlegt. Wie dies möglich ist, kann gern bei mir *(Ringo Hoffmann)* erfragt werden.
