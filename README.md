# GRK Sverige · lo-fi-prototyyppi

Klikattava prototyyppi grk.fi/se:n uudesta ruotsinkielisestä sivustosta lo-fi-tasolla. Sivut ovat GRK lo-fi -kankaan Sverige-sivulta. Ne käyttävät samoja lohkoja kuin GRK:n suomenkielinen prototyyppi. Rakenne, sisältö ja lohkot ovat sovitut, visuaalinen ilme tehdään myöhemmin. Kuvat ovat paikkamerkkejä; kaaviot ja ikonit näkyvät.

Staattiset HTML-sivut, ei build-vaihetta. Julkaisupeili esittelyä varten, ei näy hakukoneissa (`noindex` ja `robots.txt`).

## Sivut

Startsida, Tjänster, Markentreprenad och anläggning, Grundläggning, Broar, Järnväg och industrispår, Miljöteknik, Samverkan, Planering tillsammans, Datacenter, Energi och kraftnät, Industri, Referenser, Stegra Boden (referens), Nyheter, Om GRK Sverige, Jobba på GRK, Lediga jobb, Platschef, Projektchef, Arbetsledare, Medarbetare berättar, Kontakta oss, Kontaktpersoner ja Norra Sverige.

Linkki sivulle, jota ei vielä ole, avaa tyhjän sivun sivun nimellä. Toiminnot (haku, lataukset) näyttävät ilmoituksen. Lomakkeet eivät lähetä tietoja. Yhteyshenkilöt ovat grk.fi/se:n oikeat henkilöt (luettu 2.11.2026).

GRK:n prototyyppi: https://ollirimpilainen.github.io/grk-lofi-proto/
KSBR:n prototyyppi: https://ollirimpilainen.github.io/ksbr-lofi-proto/

## Päivitys

Sivut generoidaan kankaan tiedostoista: `GRK/multisite/tools/se_proto.py <kankaan project> <assetit> <archivo.woff2> <navigaatio-proto/index.html> <kohde>`. Valikko on määritelty se_proto.py:ssä, koska navigaatioprotossa ei ole Ruotsin sivustoa. SEO-otsikot: `GRK/sisaltobriefi/seo-geo-se-2026-11-02.md`.
