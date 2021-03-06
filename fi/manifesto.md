# API-manifesti


## 1. Palvele digitaalisesti rajapintapalvelun avulla

Suunnittele tietotekniikkaan pohjautuva digitaalinen palvelu- ja ohjelmistokehitys **aloittaen rajapinnan suunnittelusta**. Kaikki **tietokoneohjelmat siirtävät tietoa rajapintojen läpi**. Rajapintoihin pohjautuvassa taloudessa (engl. API Economy) on tavoitteena palvella rajapintojen avulla sidosryhmiä sähköisesti mahdollisimman hyvin sekä organisaation sisä- että ulkopuolella. Siinä rajapinta nostetaan digitaalisen toiminnan keskiöön ja se nähdään tapana palvella digitaalisesti mahdollisimman hyvin. **Toimivat rajapinnat ovat edellytys digitaalisten ekosysteemien luomiselle ja skaalaamiselle**. Ne tuovat digitaalisille palveluille lisäarvoa ja mahdollistavat toiminnan ketteryyden. Ne myös mahdollistavat suurten ohjelmistokokonaisuuksien kehittämisen pieninä helposti hallittavina paloina (mikropalvelut), jolloin ohjelmistokehityksen riskienhallinta ja kustannustehokkuus paranevat. 

Varmista, että rajapinnalla on riittävä palvelulupaus (engl. Service-Level Agreement, SLA) ja laita palvelulupaus julkisesti nähtäville. Rajapintapalvelun kannalta on tärkeää, että sen tarjoama rajapinta sekä toiminnallisesti luotettava että tietoturvallinen. Kehittäjille pitää tarjota riittävä luottavuus rajapinnan toiminnalle ja olemassaololle, jotta kehittäjät kiinnostuvat rajapinnasta.

*Kommentti: 1990-luvulla oli tärkeää luoda organisaatiolle omat internetsivut. Nykyään on tärkeää tarjota mahdollisimman hyvä & avoin rajapinta, jonka päälle sidosryhmät voivat rakentaa erilaisia käyttöliittymiä & käyttökokemuksia eri päätelaitteille. Sidosryhmät voivat jalostaa rajapinnan tarjoamaa tietoa mitä erilaisimmin tavoin. Toimivan rajapinnan avulla teknologian ja toimintaympäristön muutoksiin on helpompi reagoida nopeammin. Rajapintojen tulee olla luottettavia ja toimivia, jolloin niiden toimivuus on taattu vuosiksi eteenpäin. Ilman hyvää palvelulupausta rajapinnan on vaikeaa menestyä tai erottua muista rajapinnoista, koska kehittäjillä ob aina vara valita.*


## 2. Suosi avoimuutta

**Avoimuus tuottaa tutkitusti parempaa laatua nopeammin**. Avoin toimintatapa alusta asti minimoi turhan työn. Avoimuuden avulla palvellaan paremmin ja ketterämmin. Sisällön avoin lisenssi mahdollistaa innovoinnin ja uudelleenkäytön myös liiketoiminnassa. Avoin rajapinta tekee sen takana olevan sisällön käytöstä helpompaa. Sisällytä tietojärjestelmähankintoihin avoin rajapinta aina kun mahdollista. Katso avoimen rajapinnan määritelmä osoitteesta: http://avoinrajapinta.fi.


## 3. Tee käyttöönotosta mahdollisimman helppoa

Laatu tarkoittaa myös hyvää saavutettavuutta. Rajapinnan kohdalla sillä tarkoitetaan sekä helppoa löydettävyyttä että käytettävyyttä. **Laadukkaan rajapinnan käytön oppii mahdollisimman nopeasti**. Hyvällä rajapinnalla on **hyvä ajantasainen dokumentaatio**, jonka löytää helposti. Hyvässä dokumentaatiossa on myös **runsaasti tapaus- ja koodiesimerkkejä rajapinnan hyödyntämisestä**. Muita keinoja parantaa kehittäjäkokemusta ovat muun muassa kehitysympäristöt, rajapintaluettelot, automatisoitu API-avaimien luominen (käytön seurantaa varten) sekä **palautekanava rajapinnan omistajan ja kehittäjän välillä**. Palautekanavaksi suositellaan jotain avointa, viestit arkistoivaa foorumia. Käytä kehittäjäportaalia kokoamaan materiaali helposti saavutettavaksi, mielekkääksi kokonaisuudeksi. Edellä mainitut asiat sisältävästä kokonaisuudesta käytetään nimeä **rajapintapalvelu**. Tue rajapinnan päälle rakentavaa kehittäjää eri tavoin mahdollisimman kattavasti. Esimerkiksi puhelinpalvelu (arkisin kello 9-16), wiki ja sähköposti (alle 3 päivän vastaustakuulla) ovat hyviä tapoja tukea ja huokutella kehittäjiä.

*Kommentti: Uusi käyttäjä pystyy ottamaan parhaimmat rajapintapalvelut käyttöön alle viidessä (5) minuutissa. Rajapinnat on luotettavia (ei käyttökatkoja) ja niiden kehitys/olemassa olo on avattu vuosiksi eteenpäin. Yksi suurimmista ongelmista rajapinnoissa on edelleen se, että niiden käyttöönotto kokeilemisen avulla vie aikaa, kun niitä käsittelevä dokumentaatio on puutteellista. Hyvässä dokumentaatiossa tarjotaan eri tarpeisiin valmiita ja toimivia esimerkki-koodeja rajapintakyselyihin (esimerkiksi Python & javascript), joita voi sitten lähteä kehittämään eteenpäin, eikä pyörää tarvitse keksiä uudestaan.*

## 4. Mittaa, opi palautteesta ja iteroi

Sitä saat, mitä mittaat. **Rajapinnan käytön mittaaminen on palautetta, josta rajapinnan tarjoajan kannattaa oppia jatkuvasti**. Palaute mahdollistaa iteraation, jolla tarkoitetaan **rajapinnan jatkuvaa kehittämistä pienin ja helposti hallittavin askelin**. Muista kuitenkin rajapinnan versiointi tarvittaessa. Rajapinnan kehityksessä kannattaa pyrkiä jatkuvaan yhteistyöhön sen asiakkaiden kanssa. Vain siten tiedät, mitä tarvitaan ja teet turhaa työtä mahdollisimman vähän. Mieti myös ulkoisten rajapinnan toimintaa testaavien työkalujen hyödyntämistä, joiden avulla ymmärrät muiden käyttäjäkokemusta paremmin.

*Kommentti: Rajapinnan käytön mittaaminen on tärkeä osa sen suunnitelua. Käytännössä voit mitä ketä rajapintaa käyttää (esimerkiksi IP-osoite, API-avain, käyttäjän tunnistus) ja koska (päivämäärä, kellonaika) ja mitä tietoa rajapinnan kautta käytetään ja millä tavoin.*

## 5. Tee yhteistyötä muiden kanssa
Monella taholla voi olla samankaltaisia rajapintatarpeita. Selvitä yhteistyön mahdollisuus ja minimoi päällekkäinen työ. Esimerkiksi 6Aika-kaupungit (Helsinki, Espoo, Vantaa, Tampere, Turku ja Oulu) ovat suunnitelleet rajapintoja yhdessä sen sijaan, että jokainen kaupunki tekisi työn itsenäisesti. Tekemällä yhteistyötä avoimesti myös kehittäjäyhteisön kanssa saadaan parempi lopputulos. Opi myös aiemmista projekteista.

*Kommentti: Rajapinnan takana oleva informaatio on harvoin täydellistä. Nopein tapa parantaa sen laatua on yhteisön antama palaute. Yhteisöt voivat auttaa myös luomalla koodiesimerkkejä, jotka puolestaan helpottavat rajapinnan käyttöönottoa. Hyvien rajapintojen ympärille muodostuu elävä ja monipuolinen, kaikkia hyödyttävä ja auttava ekosysteemi.*


## 6. Toteuta johdonmukaisesti

Rajapinnat tehdään johdonmukaisesti toteuttajasta ja toteutustavasta riippumatta. Niissä käytetään samoja suunnittelumalleja, mutta niihin jätetään myös liikkumatilaa. Kaiken kattava standardointi on mahdottomuus. Perusteelliset monen sadan sivun vaatimusmäärittelyt ovat yleensä vanhentuneita jo valmistuessaan, koska maailma muuttuu päivä päivältä nopeammin. Kannattaa pyrkiä siihen, että rajapinnat toimivat yhdenmukaisesti. Julkisen sektorin avointen rajapintapalvelujen sisältö tulee tarjota yhden lisenssin alla. Myös rajapintapalvelun käyttöehdoissa pyritään yhdenmukaisuuteen. Käytä kansainvälisiä standardeja aina kun mahdollista. Standardit auttavat harmonisoinnissa ja helpottavat hyödyntämistä.


## 7. Tee tarkoituksenmukaisia rajapintoja

**Hyvä rajapinta vastaa tiettyyn tarpeeseen**. **Rajapinnalla tulee olla julkisesti suunniteltu ja julkaistu elinkaari**. Rajapinta (1) suunnitellaan, (2) toteutetaan, (3) hyödynnetään ja lopulta (4) poistetaan käytöstä. Rajapinta on osa tämän päivän käyttöliittymäsuunnittelua, jossa huomioidaan myös sovellukset ihmisten rinnalla. Rakenna tarkkaan rajattuja, käytännöllisiä ja helposti käyttöönotettavia rajapintoja. Yksi hyvä mittari rajapinnan laadulle on se, kuinka nopeasti ja helposti sen pystyy ottamaan käyttöön.

*Kommentti: Julkaise rajapinnan dokumentaatiossa sen suunniteltu elinkaari (tulevaisuuden päivitykset, versiot jne.) ja päivitä suunnitelmaa säännöllisesti*
