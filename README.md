# Východ a západ slunce: kde bude nejhezčí

Stránka, která v okruhu kolem zadaného místa najde 10 nejlepších míst na východ nebo západ slunce
a u každého řekne skóre 0–100 a čas, do kdy tam být.

Živě: https://chaloupecky.github.io/vychod-slunce/

Co se hodnotí: čistý obzor ve směru slunce, vysoká oblačnost na barvy, mlha a inverze,
výhled podle terénu, les (hledá se volná plocha), vítr a srážky.

- Počasí: [Open-Meteo](https://open-meteo.com) (zdarma, jen nekomerční použití)
- Výšková mapa: Mapzen Terrain Tiles na AWS
- Les a názvy míst: OpenStreetMap (dlaždice, Overpass, Nominatim)
- Mapa: Leaflet, podklad OpenStreetMap / OpenTopoMap

Všechno běží v prohlížeči, bez serveru a bez API klíčů. Skóre je odhad, před cestou se vyplatí zkontrolovat webkameru.
