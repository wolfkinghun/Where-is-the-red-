#Git verziokezeles

#helyi repo_letrehozasa

- a helyi repo inicializálása:
    > git init 
- ellenorzes:
    > git status
- elokeszitjuk a kommitolásra (beindexelődnek-stage):
    > git add .
- Username, email ellenőrzése:
    >git config user.name 

    > git config user.email
- létrehozzuk a legújabb verziót, 
eltároljuk a helyi repoba: 
     > git commit -m "first commit"
- ellenőrzés:
    > git status
## összekapcsolás a távoli repoval

-új GitHub repo létrehozása (publikusan)
- összekapcsolási parancs:
    > git remote add origin https://token_iskola@github.com/wolfkinghun/**repo name**.git