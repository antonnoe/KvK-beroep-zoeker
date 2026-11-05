# CLAUDE.md

Repo: KvK-beroep-zoeker

## Wat dit is

Een statische beroepenchecker (titel: Beroepenchecker Frankrijk, Check Eisen en Instanties): welke eisen en instanties gelden voor een beroep in Frankrijk, met doorverwijzing naar de beroepsorden.

## Live adres

Niet in de repo vastgelegd. De pagina verwijst naar infofrankrijk.com/beroepenchecker-werken-of-ondernemen-in-frankrijk/.

## Opbouw

- index.html: de hele tool (inline CSS en JavaScript)
- LICENSE

## Techniek

Eén HTML-bestand, geen buildstap, geen package.json. Voor een postcode wordt de gemeente opgezocht via de open API geo.api.gouv.fr; links naar beroepsorden zoals ordre-infirmiers.fr, cnb.avocat.fr en architectes.org.

## Externe diensten en namen van omgevingsvariabelen

geo.api.gouv.fr (openbaar, zonder sleutel). Geen omgevingsvariabelen.

## Hoe het live gaat

Niet in de repo vastgelegd (geen vercel.json, CNAME of workflow).

## Regels en besluiten

Nog geen vastgelegd.

Laatst nagelopen: 5 november 2026
