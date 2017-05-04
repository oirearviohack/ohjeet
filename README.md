# Ohjeet
Oirearviohack-tapahtuman taustamateriaali ja ohjeistus

## ODA-palveluiden kehitysympäristö
ODA-palveluiden kehitysympäristö toimii osoitteessa https://oda.medidemo.fi/. Palvelimen juurihakemistossa toimii ODA-palveluiden käyttöliittymäkoodi. Samalla palvelimella ovat myös sekä omatietoja sisältävä ODA PHR-palvelu että edustapalvelu ODA FHIR Service.

ODA PHR -palvelua (https://oda.medidemo.fi/phr) voi kehityskäytössä käyttää ilman autentikoitumista. Käyttöliittymän kautta pääsee selaamaan palvelussa jo olevia esimerkkisisältöjä, syöttämään uusia tietoja ja muutenkin oppiskelemaan toteutuksen toimintaa. PHR-palvelu perustuu HAPI-toteutukseen (ks. http://hapifhir.io/).
 
ODA FHIR Service (https://oda.medidemo.fi/fhir) toimii edustapalveluna, joka hoitaa mm. autentikoinnit ja auttaa kertakirjautumisen (SSO) toteuttamisessa. Mikäli tahdot käyttää FHIR Serviceä, voit Oirearviohackin ajan käyttää erityistä system-tason access tokenia:

```Authorization: Bearer eyJhbGciOiJSUzI1NiJ9.eyJyb2xlcyI6W3sicm9sZSI6IlNZU1RFTSJ9XSwiZXhwIjoxNDk1MTA0MTk5LCJpYXQiOjE0OTM4OTQ1OTksImp0aSI6IjQ2ODhjMjkwLTg2NWYtNGUwNS05NmIwLWM3ZDNjZjk4MWRmMSJ9.aaaeT8OFXfP0rdkd3Gz4LVW1qo5XjCHPlDE6Kh4gthDPXKqjU07ombdpubK5aBGA8u9oHrSe8HglM6r7aKrd1w9LakVTJffFJDfZahzKJI2p5Q8TAAKj96YtuX0fHNNC-iCwG3v_JC2h_cjDeTH-3xKkaW2Cd19jwqAG6wYUj_uo6wdMHHG0MR4iBx8-Me41cf7I5nAujcSkp2pWxH58yUP_MNk2qoHCvWMcgxHlNtwwBDLQeiJY8PBskdVs8XqgfpWe-O6MzKJkZO3bTVGkLriXXHc8VW99HocSNzrFDsXpVEjg_9XgwO7KwGUcGQrxpeaT5LJPPq3C1LtePfDxiQ```


 
