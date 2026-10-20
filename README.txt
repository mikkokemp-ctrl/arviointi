ARVIOINTI – IPHONE-ENSISIJAINEN PWA

Sisältö:
- index.html: sovellus
- manifest.webmanifest: asennettavan sovelluksen tiedot
- sw.js: offline-välimuisti
- icon-192.png ja icon-512.png: sovelluskuvakkeet

TÄRKEÄÄ
PWA:n asennus iPhonen kotinäyttöön edellyttää, että tiedostot avataan HTTPS-osoitteessa (tai kehityksessä localhostissa). Pelkkä HTML-tiedoston avaaminen Tiedostot-sovelluksesta ei mahdollista luotettavaa PWA-asennusta eikä offline-välimuistin rekisteröintiä.

Tietosuoja:
- Oppilas- ja arviointitiedot tallennetaan selaimen localStorageen tällä laitteella ja tämän verkkosivun osoitteen alla.
- Sovellus ei lähetä oppilastietoja palvelimelle eikä sisällä tietokantapalvelinta.
- HTTPS-hostaus palvelee vain sovellustiedostot. Se ei itsessään synkronoi tai vastaanota arviointitietoja.
- Älä tyhjennä Safari-verkkosivustojen tietoja; tee JSON-varmuuskopio säännöllisesti.
- Älä käytä samaa jaettua laitetta ilman suojausta oikeisiin oppilastietoihin.

ASENNUS IPHONEEN
1. Julkaise tämän kansion sisältö staattisena verkkosivuna HTTPS-osoitteeseen (esim. GitHub Pages tai muu staattinen hostaus).
2. Avaa julkaistu osoite iPhonen Safarissa.
3. Paina Jaa -> Lisää Koti-valikkoon -> Lisää.
4. Käynnistä Arviointi-kuvakkeesta. Avaa sovellus ensimmäisen kerran verkkoyhteydessä, jotta offline-tiedostot välimuistitetaan.

Käyttöönotto ja testaus:
- Testaa ensin ilman oikeita oppilastietoja.
- Lisää testiryhmä, tallenna arviointityö, sulje sovellus ja avaa se uudelleen.
- Tee varmuuskopio Tiedot ja varmuuskopio -välilehdeltä.

OPS-huomio: tavoitepohja on muokattava työskentelypohja eikä Espoon OPSin sanatarkasti varmennettu virallinen tavoiteluettelo.
