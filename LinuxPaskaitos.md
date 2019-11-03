#Paskaita 1
#Paskaita 2
Apvalkalas - programa, kur įvestas programas perduoda operacinei sistemai. Naudojant apvalkalą paleidžiamos programos naudoja komandinės eilutės sąsają. Pagal Unix filosofiją, programos yra mažos ir skirtos konkrečiam darbui.

Komandos struktūrą sudaro komandos vardas, nebūtini raktai ir komandos argumentai.
Svarbiausių komandų žodynėlis:

- `date +<formatas>` - datos spausdinimas norimu formatu;
- `man <komanda>` - informacija apie komandą;
- `<komanda> --help` - informacinis puslapis;
- `echo <tekstas>` - teksto spausdinimo programa;
- `cat <failas>` - failo rodymo programa;
- `whoami` - spausdina vartotojo vardą;
- `ls` - spausdina failų pavadinimus
- `pwd` - spausdina esamos direktorijos pavadinimą
- `cd` - keičia direktoriją
- `grep` - paieškos komanda
- `exit` - uždaro terminalo langą


Pakaitos simboliai:

- `?` - bet koks vienas simbolis
- `*` - bet kokie simboliai (arba tuščias simbolis)

Literatūra:
1. https://tutorials.ubuntu.com/tutorial/command-line-for-beginners#0
2. https://www.howtogeek.com/412055/37-important-linux-commands-you-should-know/
3. https://www.linux.com/tutorials/how-use-linux-command-line-basics-cli/

#Paskaita 3
#Paskaita 4
Failų sistema – duomenų struktūrų, algoritmų ir sąsajų visuma, leidžianti įrašyti, išsaugoti ir perskaityti laikmenoje ar kompiuterių tinkle esančią struktūruotą informaciją, nesigilinant į technines informacijos išsaugojimo detales. Vartotojui svarbu suprasti pagrindinius failų saugojimo ir apsaugos principus.

Failai yra saugomi failų sistemoje, kuri leidžia teisingai interpretuoti duomenis. Paprastam vartotojui užtenka žinoti failo vardą, o ne kaip duomenys saugomi. Keli failai jungiami į katalogus, kurie sudaro hierarchinę struktūrą. Failų sistemų struktūros gali būti skirtingos, pvz. ext3, ext4, FAT-16, FAT-32, NTFS ir t.t., Linux naudojama ext3. Joje didžiosios ir mažosios raidės laikomos skirtingais simboliais, gali būti naudojami Unicode simboliai, nors ne visos senesnės programos galės juos perskaityti. Dažniausiai failų sistemoje naudojamas standartinis katalogų išdėstymas, kuris leidžia vartotojams ir programinei įrangai greičiau rasti norimus failus. Dar failai ir katalogai skirstomi pagal tai, ar juos galima bendrinti, ar ne, ir į statinius (keičiamus administratoriaus) arba dinaminius (keičiamus programinės įrangos, vartotojo). Failų ir direktorijų apsaugai naudojama priemonė - gairelės. Failus galima skaityti (r), keisti (w) ir vykdyti (x). Yra trys vartotojų kategorijos: failo/katalogo savininkas, savininko grupės vartotojai, visi kiti vartotojai. Failo gaireles gali keisti jo savininkas, failo savininką laisvai keisti gali tik administratorius. Linux branduolyje naudojamas SELinux - papildomas saugumo modulis. Jis įdiegia taisykles, kurios riboja prieigą prie failų ir tinklo išteklių, taip sumažindamas padaromą žalą programinės įrangos klaidų atveju.

Literatūra:
1. https://lt.wikipedia.org/wiki/Fail%C5%B3_sistema
2. https://www.geeksforgeeks.org/unix-file-system/
3. https://www.linux.com/tutorials/linux-filesystem-explained/
#Paskaita 5
#Paskaita 6