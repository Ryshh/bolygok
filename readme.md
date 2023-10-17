# Verziókezelés
- helyi repo inicializálása
    > git init
- megadjuk(leellenőrizzük) a Github felhasználó nevünket és email címünket
    > git config user.name
    > git config user.email
- ellenőrzés (van-e különbség a repo és a munkakönyvtár közt)
    > git status
- előkészítjük a helyi repóba való eltárolásra a fájlokat commitol- ( a verzió beindexelése megtörténik)
    > git add .
- ellenőrzés:
    > git status
- commitolás: eltároljuk az aktuális állapotot mint egy verzió
    > git commit -m "first commit"
- ellenőrzés:
    > git status
- az összes verzió megjelenitése:
    > git log
- távoli repo létrehozása: **Github**
- helyi repo összekapcsolása a  távolival:
    > git remote add origin https:// **token@** github.com/Ryshh/repoName.git
- **első** push parancs alkalmával meg kell mondani melyik ágba(branch) kerüljön:
    > git push -u origin master/main
- fogja kérni a tokent, kimásoljuk:
    > RMB+Enter
- a következő módosításkor:
    > git push