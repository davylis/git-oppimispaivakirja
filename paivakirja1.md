# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Menin hieman sekaisin tehtävänannon kanssa kun kloonasin repon, mutta ajttelin että forkkaan sen omiin repoihin ja sitten kloonaan sieltä.
Kaikki tehtävät semi simppelit, näitä on tullut käytettyä projekteissa. Uutta oli staging alueelta muutoksen poistaminen.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git clone https://github.com/mruonavaara/git-oppimispaivakirja | kloonaa repon koneelleni |
| git branch -a | näyttää olemassaolevat haarat |
| git checkout paivakirja | vaihtaa haaran |
| git add paivakirja1.md | Lisää tiedoston muutokset staging alueelle |
| git commit -m "Testi" | tallennetaan commit tilaan |
| git push origin paivakirja1| lähettää commitin etärepoon |
| git remote set-url origin git@github.com:davylis/git-oppimispaivakirja.git | päivittää olemassaolevan etärepon url |
| git remote add origin git@github.com:davylis/Git.git | tähän lyhyt kuvaus, mitä komento tekee |
| git remote -v | tähän lyhyt kuvaus, mitä komento tekee |
| git push -u origin main | Kuvaus |
| mkdir harjoitus2 | uuden repon luonti |
| cd harjoitus2 | siirrytään repoon |
| echo "Hei maailma!" > hello.html | muokataan tiedostoa eccholla bashissä |
| vim hello.html | muokataan tiedostoa vimissä |
| git mv hello.html index.html | mv vaihtaa nimen |
| git rm test.txt | rm poistaa |
| git log | näyttää commit historian |
| git restore --staged kolmas.txt | poistaa tiedoston staging alueelta |
| git restore --staged . | poistaa kaikki muutokset staging alueelta |
| git restore toinen.txt | hylkää paikalliset muutokset ja palauttaa viimeiseen commit tilaan |
| git clean -f | poistaa kaikki ulkopuoliset tiedostot |
| git revert HEAD | luo uuden commitin joka peruuttaa viimeisimmän commitin historiasta |
| git log --oneline | näyttää commit historian per rivi |
| git checkout master | vaihtaa master haaraan |
| git checkout -b tyylit | luo uusi haara ja siirry siihen |
| git merge tyylit | yhdistöö haaran master haaraan |
