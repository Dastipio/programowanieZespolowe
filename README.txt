Instalcja express i body_parser
1) W katalogu progr_zesp_server otw�rz cmd i wpisz 'npm install express' -> enter, a nat�pnie wpisz 'npm install body-parser' -> enter
2) powt�rz w katalogu progr_zesp


Odpalenie projektu:
    I. Front-end:
	1) przechodzimy do katalogu progr_zesp i odpalamy cmd
	2) wpisujemy 'node frontEndServer.js'
	3) uruchamia si� serwer i mo�emy w przegl�darce wpisa� 'localhost:3000'
	4) front end dzia�a
    II. Back-end:
	1) przechodzimy do katalogu progr_zesp_server i odpalamy cmd
	2) wpisujemy 'node backEndServer.js'
	3) back end dzia�a

UWAGA!:
	Poniewa� node.js wymaga ka�dorazowego prze�adowanie po jakiejkolwiek zmianie, dobrze jest zainstalowa� sobie co� w stylu nodemon
'npm install nodemon -g' (-g instaluje globalnie)
apke odpalamy wtedy: 'nodemon fronEndServer.js' i analogicznie 'nodemon backEndServer.js'

Baza danych:
1) Pobierz XAMPP i zainstaluj
2) Uruchom jako Administrator, zainstaluj i uruchom Apache oraz mysql service
3) Kliknij 'Admin' obok mysql (odpali si� phpMyAdmmin)
4) Klik na mysql i 'Import' na pasku na �rodku na g�rze 
5) Podaj �cie�k� do room_reservation.sql i kliknij OK
6) Enjoy


MySql - JS connector:
https://www.sitepoint.com/using-node-mysql-javascript-client/
