# paskirstytos
README failas, kuriame paaiškinama, kaip sukurti ir paleisti konteinerius.

Konteineris "calcapp" sukuriamas "httpd:2.4" "image" pagrindu, į kurį "/usr/local/apache2/htdocs/" lokacijoje yra įkopijuojamas "index.html" failas
"index.html" - vienintelis aplikacijos failas, kuriame yra visi html, css ir js elementai.

Taipogi naudojamas httpd.conf failas, kuris yra įkopijuojamas vietoj "/usr/local/apache2/conf/httpd.conf" failo

Kitas konteineris "ngnix" yra kuriamas paleidimo metu.







"calculator" - web-aplikacija kurioje galime atlikti aritmetinius veiksmus 




Apkrovos balansavimo sąrankos ir visų naudojamų tinklo konfigūracijų dokumentacija.



Docker-compose.yml



Apkrovos balansavimui yra naudojamas "nginx".
Oficialus "nginx" image'as yra pritaikomas naudojant "nginx.conf" failą. Kuriame serveriui priskiriamas "80" portas ir visas užklausos į jį yra peradresuojamos vienam iš X skaičiaus klientų, kuriuose yra paseikiamas skaičiuotuvas.









