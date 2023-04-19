# Webová mapová aplikace pro lokalitu Nečtiny.

mapa: https://venca275.github.io/leafletapp_nectiny/

## Aktualizace bodového pole
Pro aktualizaci bodového pole je nutné vyplnit ve správném formátu informace o nových bodech do tabulky xls, kterou následně stáhnete ve formátu CSV, který musíte převést pomocí convertoru uvedeného níže a nahrát do složky "data"\
Na níže, uvedeném linku převedete CSV do GEOJSONU, který lze následně nahrát do složky, data a nahradit tím původní soubor(zkontrolovat jestli název sedí s původním souborem, jinak nebude fungovat(např. trigonometricke_body). Také se nesmí měnit jména sloupců). \
Trigonometrické body: https://docs.google.com/spreadsheets/d/1WwdZLG7cznmaWxbvLW9Dh32ygGsZdkotd6pmdjcRZbQ/edit?usp=sharing \
Nivelační body: https://docs.google.com/spreadsheets/d/1GDaGFvLHtiSU2rokVfMx4hcGpaxkWi-i-RWo1GSmT5Y/edit?usp=sharing \
Converter: https://www.convertcsv.com/csv-to-geojson.htm \
data: https://github.com/venca275/leafletapp_nectiny/tree/main/data \
 ### Convertor
 - První krok v convertoru je nahrání csv souboru(rovnou doporučuji zkontrolovat jméno souboru i před nahráním)\
 - Druhý je v "OUTPUT OPTIONS" definovat pole zeměpisné šířky a délky.\
 - V případě trigonometrických bodů (Latitude Field # '7', Longitude Field # '6' ) \
 - V případě nivelačních bodů (Latitude Field # '6', Longitude Field # '5' ) \

