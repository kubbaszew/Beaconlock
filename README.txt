1. Wszystko znajduje sie w [...]/node_modules/noble/examples

2. Całość uruchamia się sudo python [...]/node_modules/noble/examples/main.py

<na początku jest dodana linijka na potrzeby pokazu ktora kasuje wszystkie logi i dane logowania z poprzednich uruchomien>

3. launcher.py to front-end ktory obsluguje logowanie i pobiera adresy MAC z serwera
po pierwszym zalogowaniu dane usera sa zapisane user.cfg

4. blokowanie i odblokowywanie jest w scan2.js 
zeby uruchomic tylko to nalezy wpisac sudo node [...]/node_modules/noble/examples/scan2.js
