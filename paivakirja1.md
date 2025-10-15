# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Menin hieman sekaisin tehtävänannon kanssa kun kloonasin repon, mutta ajttelin että forkkaan sen omiin repoihin ja sitten kloonaan sieltä.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git clone https://github.com/mruonavaara/git-oppimispaivakirja | kloonaa repon koneelleni |
| git branch -a | näyttää olemassaolevat haarat |
| git checkout paivakirja | vaihtaa haaran |
| git add paivakirja1.md | Lisää tiedoston muutokset staging alueelle |
| git commit -m "Testi" | tallennetaan commit tilaan |
| git push origin paivakirja1| lähettää commitin etärepoon |

### remote: Permission to mruonavaara/git-oppimispaivakirja.git denied to davylis.
### fatal: unable to access 'https://github.com/mruonavaara/git-oppimispaivakirja/': The requested URL returned error: 403

| git remote set-url origin git@github.com:davylis/git-oppimispaivakirja.git | päivittää olemassaolevan etärepon url |
