---
title: PP2 Tracker – tietosuojaseloste / Privacy policy
---

# PP2 Tracker – tietosuojaseloste / Privacy policy

*Päivitetty / Updated: 12.11.2026*

## Suomeksi

**PP2 Tracker** on epävirallinen apuohjelma Pro Pilkki 2 -pelille. Se laskee kisan tuloksen
pelin ruudulta luetuista kalaviesteistä. Sovellus ei ole Procyon Products Oy:n tai pelin
tekijöiden tuote eikä heidän hyväksymänsä.

### Mitä tietoja sovellus käsittelee

- **Ruudun sisältö.** Kun painat *Aloita ruudun luku*, Android kysyy lupaa ruudun jakamiseen.
  Sovellus lukee ruutua vain laitteessa: se etsii pelin nostoviestit (laji ja paino) ja
  kisatyypin ja laskee tuloksen. **Ruutukuvia ei tallenneta eikä lähetetä minnekään.** Ainoa poikkeus: jokaisesta lasketusta kalasta sovellus säilyttää laitteen väliaikaisessa muistissa pienen rajauksen pelin viestialueesta (ei koko ruutua), viimeiset kahdeksan. Ne ovat vikaraporttia varten eivätkä lähde laitteesta, ellet itse lähetä vikaraporttia. Ruudun
  luku päättyy, kun painat *Lopeta ruudun luku* tai suljet ilmoituksen.
- **Testikuva (valinnainen).** Jos painat itse *Tallenna testikuva*, yksi ruutukuva ja siitä
  luetut nostot tallennetaan laitteen sovelluskohtaiseen kansioon. Ne eivät lähde laitteesta,
  ellet itse lähetä niitä.
- **Kisaloki.** Kisan tapahtumat (kellonaika, kalalaji, paino, kisatyyppi) tallentuvat
  tekstitiedostoon laitteen kansioon *Lataukset/PP2 Tracker/kisalokit*. Voit poistaa ne
  milloin tahansa.
- **Vikaraportti (valinnainen).** Jos painat itse *Lähetä vikaraportti*, sovellus kokoaa
  zip-tiedoston: sovelluksen versio, puhelimen malli ja Androidin versio, asetukset,
  tapahtumaloki, viisi viimeisintä kisalokia, viimeisimpien laskettujen kalojen ja lukematta jääneiden rivien nostoalueen
  kuvat, uusin itse tallentamasi testikuva ja kirjoittamasi kuvaus sekä satunnainen asennustunniste. Jos olet itse painanut kelluvan palkin
  kamerapainiketta, mukana on myös koko ruudun kuva (esimerkiksi pelin tuloslista, jossa
  näkyvät muiden pelaajien nimimerkit; kuvan voi tallentaa vain painamalla nappia). Mukana ei
  ole nimeäsi. Sovellus ei lähetä tiedostoa itse, vaan avaa Androidin jakovalikon, jossa valitset
  itse vastaanottajan. Jos et jaa tiedostoa, se ei lähde laitteesta.
- **Asetukset.** Valitsemasi kieli tallentuu laitteelle.

### Verkko ja kolmannet osapuolet

- **Google Playn kautta jaettu versio ei käytä verkkoa lainkaan.** Sillä ei ole
  internet-oikeutta.
- GitHubista ladattavassa versiossa on päivitystarkistus, joka kysyy GitHubista uusimman
  version numeron enintään kerran vuorokaudessa. Pyynnön mukana ei lähetetä mitään tietoja
  sinusta; GitHub näkee pyynnön kuten minkä tahansa nettisivun avauksen (esimerkiksi
  IP-osoitteen).
- Tekstintunnistus tehdään laitteessa Googlen ML Kit -kirjastolla, jonka malli on mukana
  sovelluksessa. Kirjaston käyttötilastojen lähetys on poistettu käytöstä.
- Sovelluksessa ei ole mainoksia, analytiikkaa, tilejä tai seurantaa. Tietoja ei myydä eikä
  luovuteta kenellekään.

### Oikeudet ja miksi niitä tarvitaan

- **Ruudun jako (MediaProjection):** nostoviestien lukemiseen pelistä.
- **Näkyminen muiden sovellusten päällä:** tulospalkin näyttämiseen pelin päällä.
- **Etualan palvelu ja ilmoitukset:** ruudun luvun ajaksi näytettävä ilmoitus, josta sen voi
  lopettaa.

### Lapset

Sovellus ei ole suunnattu lapsille, eikä se kerää tietoja kenestäkään.

### Yhteystiedot

Kysymykset: **nousiainenlassi@gmail.com**

---

## In English

**PP2 Tracker** is an unofficial helper app for the mobile game Pro Pilkki 2. It calculates
the result of a fishing contest from the catch messages shown on the game screen. It is not a
product of, or endorsed by, Procyon Products or the makers of the game.

### What data the app handles

- **Screen content.** When you press *Start screen reading*, Android asks for permission to
  share your screen. The app reads the screen only on your device: it looks for the game's
  catch messages (species and weight) and the contest type and calculates the result.
  **Screenshots are not stored or sent anywhere.** The only exception: for each counted fish the app keeps a small crop of the game's message area (not the full screen), the last eight, in the device's temporary storage. They are for the bug report and do not leave the device unless you send a bug report yourself. Reading stops when you press *Stop screen
  reading* or close the notification.
- **Test image (optional).** Only if you press *Save test image* yourself, one screenshot and
  the catches read from it are saved to the app's own folder on your device. They do not leave
  the device unless you send them yourself.
- **Contest log.** Events of a contest (time, species, weight, contest type) are saved to a
  text file in *Downloads/PP2 Tracker/kisalokit* on your device. You can delete them at any
  time.
- **Bug report (optional).** Only if you press *Send bug report* yourself, the app bundles a
  zip file: the app version, phone model and Android version, settings, the event log, the
  five latest contest logs, images of the catch-message area for the latest counted fish and for rows that could not be read, the
  latest test image you saved yourself, the description you write and a random installation ID. If you yourself pressed the floating bar's camera button, a full-screen image is included too (for example the game's results list, which shows other players' nicknames; it is saved only when you press the button). It does not include your name.
  The app does not send the file by itself; it opens Android's share menu where you choose
  the recipient. If you do not share the file, it does not leave the device.
- **Settings.** The language you choose is stored on the device.

### Network and third parties

- **The version distributed through Google Play does not use the network at all.** It has no
  internet permission.
- The version downloaded from GitHub has an update check that asks GitHub for the latest
  version number at most once a day. No information about you is sent with the request;
  GitHub sees it like any web page visit (for example, your IP address).
- Text recognition runs on the device with Google's ML Kit library; the model is bundled
  with the app. Sending of the library's usage statistics has been disabled.
- The app has no ads, analytics, accounts or tracking. Data is not sold or shared with anyone.

### Permissions and why they are needed

- **Screen sharing (MediaProjection):** to read catch messages from the game.
- **Display over other apps:** to show the result bar on top of the game.
- **Foreground service and notifications:** a notification is shown while screen reading is
  on, from which it can be stopped.

### Children

The app is not directed at children and does not collect data from anyone.

### Contact

Questions: **nousiainenlassi@gmail.com**
