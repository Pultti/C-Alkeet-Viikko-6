Tiedostojen käsittely

1. Kirjoita ohjelma, joka kysyy käyttäjän nimen ja tallentaa sen tiedostoon.

2. Luo jollain editorilla (esim. Notepad) tiedosto nimeltään source.txt jossa seuraavat tiedot
Matti, Mainio, Oulu, 28
Jussi, Jonio, Turku, 32
Liisa, Joki, Tampere, 24
Aino, Virta, Oulu, 23
Liisa, Joki, Tamprere, 28
Kirjoita sitten ohjelma, joka lukee tiedostoa ja kirjoittaa uuden tiedoston nimeltään target.txt, jossa
kaikki pilkut on korvattu puolipisteellä.

3. Kirjoita ohjelma, joka laskee tiedostossa olevien sanojen ja rivien määrän.
Käytetään sääntönä, että sanojen erottimena toimii vain välilyönti.

4. Kirjoita ohjelma,
-jossa on tietue nimeltään Student, jossa seuraavat kentät:
• id INT
• name CHAR(50)
• age INT
-Luo Student-tyyppinen taulukko, johon voidaan tallentaa 5 alkiota.
-Lisää koodi, jolla käyttäjältä kysellään viiden opiskelijan tiedot ja ne tallennetaan em. taulukkoon.
-Lisää koodi, jolla em. opiskelijoiden tiedot tulostetaan ruudulle.

5. Kirjoita ohjelma, joka toimii kuten edellinen sovellus, mutta lopuksi ohjelma kysyy:
• Haluatko tallentaa tiedot (Kyllä=1 /Ei=2)?
• Jos käyttäjä vastaa 1(eli Kyllä), tiedot kirjoitetaan tiedostoon nimeltä c:/temp/students_data.txt
siten, että:
• Kunkin opiskelijan tiedot kirjoitetaan omalle rivilleen
• kenttien väliin tulee pilkku
• Tarkista esim. Notepadillä, että tiedoston muoto on oikein

6. Kirjoita ohjelma, joka kysyy käyttäjältä opiskelijan ID:n. Sitten ohjelma etsii tiedostosta
c:/temp/students_data.txt annettua ID:tä vastaavan opiskelijan tiedot ruudulle, jos annettua id:tä
ei löydy, tulosta teksti ”Antamaasi id:tä ei löydy”.
      OHJE: Tee silmukka, jota suoritetaan niin kauan kuin tiedostossa on merkkejä
      -Lue tiedostosta funktiolla fscanf rivin ensimmäinen ”sana” kokonaislukumuuttujaan id
