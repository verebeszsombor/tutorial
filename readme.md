Github segédlet
VSC terminál - git bash (ha nincs ilyen, akkor Git SCM telepítése)
mkdir tutorial - make directory tutorial nevű mappa
cd tutorial - change directory
echo "Github segédlet" >> readme.md - readme.md fájl létrehozása és a szöveg beszúrása
git init - mappa inicializálása
git config --global --list - globális beállítások listázása
git remote -v - távoli repo-k címének lekérdezése
git remote add origin https://github.com/verebeszsombor/tutorial.
git - távoli repo hozzáadása origin néven
git remote remove origin - origin nevű távoli repo eltávolítása
git add readme.md - változtatások mentése (staging)
git commit -m "first commit" - commit hozzáadása
git branch -m main - az ág átnevezése main-re