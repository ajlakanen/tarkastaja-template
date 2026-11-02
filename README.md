# Tarkastajapyyntö

Pieni selainlomake, joka kokoaa gradun tai diplomityön tarkastajapyyntöviestin vaihe vaiheelta.

Sivu: https://ajlakanen.github.io/tarkastaja-template/

Kaikki toimii selaimessa ([index.html](index.html)), mitään ei lähetetä palvelimelle.

## Esimerkki lopputuloksesta

Lomake kysyy työn tyypin, oppiaineen, nimen, kielen, jättöpäivän, ohjaajat, Turnitin-tilanteen, vastaustoiveen, allekirjoituksen ja tiivistelmän. Niistä syntyy tällainen viesti:

```
Hei,

etsin tarkastajaa pro gradu -tutkielmalle (tietojenkäsittelytiede) "Suurten kielimallien käyttö ohjelmoinnin opetuksessa" (liitteenä). Työ on kirjoitettu suomeksi. Työn abstrakti on alla.

Olisiko sinulla mahdollisuutta tarkastaa työ? Vaihtoehtoisesti olisiko sinulla ehdotusta kuka työlle olisi sopiva tarkastaja?

Työ on jätetty tarkastettavaksi 3.11.2026 joten tarkastuksen deadline on 3.12.2026.

Työn ohjasivat allekirjoittanut ja Pekka Peruskäyttäjä.

Turnitin-analyysi on tehty, ja voin sen toimittaa sinulle jos haluat.

Olisi hienoa jos ehtisit vastaamaan alkuviikon aikana. Kiitos etukäteen!

Maija Meikäläinen

TIIVISTELMÄ

Tutkielmassa selvitetään, miten suuria kielimalleja voidaan hyödyntää ohjelmoinnin peruskurssien opetuksessa ja millaisia vaikutuksia niillä on opiskelijoiden oppimistuloksiin. Aineisto kerättiin kyselyllä ja haastatteluilla syksyllä 2026.
```

Deadline lasketaan automaattisesti kuukausi jättöpäivästä. Jos työtä ei ole vielä jätetty, viestissä lukee sen sijaan "Opiskelija jättää työn tarkastettavaksi Vasarassa lähipäivinä."
