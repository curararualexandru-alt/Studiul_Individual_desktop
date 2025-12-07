# Comenzile_folsite_pentru_GitHub
#Toate comenzi pentru commit și push în repository

1. Inițializare și conectare repository

1.1. Inițializare proiect Git

git init – creează un repository Git în folderul actual.

Conectare la GitHub

git remote add origin <url> – conectează repository-ul local la GitHub.

2. Verificarea stării proiectului

git status – arată fișierele modificate, nesalvate sau în staging.

git log – arată istoricul commit-urilor.

git log --oneline – versiune scurtă a istoricului.

3. Gestionarea fișierelor (staging area)

 Adăugare fișiere în staging

git add <fișier> – adaugă un singur fișier.

git add . – adaugă toate fișierele modificate.

 Eliminare fișiere din staging

git reset <fișier> – scoate un fișier din staging.

git reset – scoate toate fișierele din staging.

 Ștergere fișiere din repository

git rm <fișier> – șterge un fișier din proiect.

4. Crearea commit-urilor

 Commit simplu

git commit -m "Mesaj" – salvează modificările.

 Commit detaliat

git commit -m "Titlu" -m "Descriere" – commit cu descriere lungă.

 Corectarea ultimului commit

git commit --amend – modifică ultimul commit fără a crea unu nou.

Undo commit

git reset --soft HEAD~1 – șterge ultimul commit, păstrând modificările.

git reset --hard HEAD~1 – șterge ultimul commit + modificările.

5. Lucrul cu branch-uri

Creare branch

git branch <nume_branch>

Schimbare branch

git checkout <nume_branch>

Creare + comutare

git checkout -b <nume_branch>

6. Sincronizare cu GitHub (push/pull)

Trimitere modificări pe GitHub

git push -u origin main – primul push.

git push – trimite commit-urile noi.

git push origin <nume_branch> – push pe alt branch.

Preluare modificări de pe GitHub

git pull – actualizează localul.

git pull origin main – actualizează branch-ul main.
