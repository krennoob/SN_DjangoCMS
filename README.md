# SN_DjangoCMS
1. Ustvari novo mapo (kjer želiš).
2. Odpri ukazni poziv (CMD)
3. Namesti vse potrebno (če še nimaš):
  - Python,
  - virtualenv (z ukazom "pip install virtualenv" v ukaznem pozivu),
  - Git
4. V ukaznem pozivu se premakni v novo ustvarjeno mapo.
5. V ukaznem pozivu izvedi ukaz "virtualenv ." in počakaj, da se vse stvari namestijo.
6. V ukaznem pozivu izvedi ukaz "git clone https://github.com/krennoob/SN_DjangoCMS" in počakaj, da se vse stvari namestijo.
7. V ukaznem pozivu izvedi ukaz ".\scripts\activate".
8. V ukaznem pozivu izvedi ukaz "cd SN_DjangoCMS".
9. V ukaznem pozivu izvedi ukaz "pip install -r req.txt" in počakaj, da se vse stvari namestijo.
10. V ukaznem pozivu izvedi ukaz "cd site1".
11. V ukaznem pozivu izvedi ukaz "python manage.py runserver 8080" in počakaj dokler se v ukaznem pozivu ne izpiše:
  System check identified no issues (0 silenced).
  April 15, 2023 - 17:19:17
  Django version 3.1.14, using settings 'site1.settings'
  Starting development server at http://127.0.0.1:8080/
  Quit the server with CTRL-BREAK.
12. V spletni brskalnik napiši naslov "http://127.0.0.1:8080/?edit"
13. Na strani, ki se odpre se v zgornjem levem kotu strani prijavi z:
  - uporabniškim imenom: admin
  - geslom: admin
14. V belem toolbar-u klikni smart-notebook.com > Disable toolbar.

Zdaj se lahko sprehajaš po spletni strani.
Spletni strežnik prekineš tako, da zapreš ukazni poziv ali pa v njem pritisneš kombinacijo tipk ctrl+c.
