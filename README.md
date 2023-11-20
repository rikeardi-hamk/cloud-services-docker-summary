# HAMK Pilvipalvelut - Docker mikropalveluympäristö

Tämä repo on HAMKin Pilvipalvelut kurssin docker ympäristötehtävän toteutus.

## Sisältö

- [Perustiedot](#perustiedot)
- [Asennus](#asennus)

## Perustiedot

Tehtävässä piti luoda kokonainen docker-pohjainen mikropalveluympäristö, jolla tarjotaan palvelu, jossa kuvataan ympäristön luominen.

## Asennus

Lataa paketti palvelimelle komennolla
```
git clone https://github.com/rikeardi-hamk/cloud-services-docker-summary.git
```

Siirry ladattuun kansioon ja luo kansiot tietokannoille sekä aseta niiden käyttöoikeudet.
```
cd cloud-services-docker-summary

mkdir pg-{0,1}
chown 1001:0 pg-{0,1}
```

Aja docker compose
```
docker compose up -d
```

Tämän jälkeen avaa selaimeen verkkopalvelu http://wiki.colasloth.com


&copy; Risto Lievonen