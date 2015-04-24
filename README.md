# Howtogit

Importere fra github:

1. Gå inn i ønsket mappe
2. {git clone "link til repository"}
DONE!


Commit til lokalt "workspace"

1. {git commit -a}  -> commit alle filer i workspace
2. evt konfigurere mail og navn, følg instrukser
3. {git commit -a igjen}
4. Skriv inn commitkommentar -> Ctrl+O for å skrive til disk -> enter for å committe -> Ctrl+X for å gå ut av menyen
DONE

Push til repository på nett

1. {git push origin master}
2. brukernavn = "kajakvello"
3. passord = "Zeebra12"

DONE

KOPIERE FILER TIL OG LOGGI INN PÅ ANNEN PC REMOTE

    Logging in:
        ssh username@129.241.187.### where ### is the remote IP
    Copying files between machines:
        scp source destination, with optional flag -r for recursive copy (folders)
        Examples:
            Copying files to remote: scp -r fileOrFolderAtThisMachine username@129.241.187.###:fileOrFolderAtOtherMachine
            Copying files from remote: scp -r username@129.241.187.###:fileOrFolderAtOtherMachine fileOrFolderAtThisMachine
            
            
            
HENTE COMMIT FRA HISTORY OG GJØRE DEN TIL MASTER

git fetch origin

git reset --hard YOUR_SHA_HERE
