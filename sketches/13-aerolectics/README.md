# 13 · Aerolectics

Author: bkk · Started: 2026-11-02 · Status: sketch · Stack: static HTML + JS

What changes when we understand the African girls* and young women* taken to European convents in the 19th century not as statistics or archival collateral damage, but as movements of air that resist discipline, or, in metaphorical terms, weather modification?

## Run

Online, once published: `https://gitbel8.github.io/weather-commons/13-aerolectics/`

On your computer:

```bash
cd sketches/13-aerolectics
python -m http.server 8000
```

Then open http://localhost:8000.

## 1. Event

Between the 1840s and 1870s, missionaries, above all Niccolò Olivieri, bought African girls and young women on slave markets in Egypt and brought them to convents in France, Italy, Austria, Bavaria, Slovenia and Croatia. Ute Küppers-Braun lists 557 of them. Most died within a few years. Nuns and bishops explained the deaths with the European climate, and described the girls' resistance as storms, heat and wildness to be tamed.

The title builds on Kamau Brathwaite's *tidalectics*: telling histories through the movement of tides. *Aerolectics* tries to tell these stories through movements of air.

## 2. Simulate

An interpretive map. One spiral per entry, placed at her convent town. It widens with each year between arrival and death. Where no death is recorded, it has not ended and keeps turning. Deaths recorded as affecting lungs or breath are drawn as a breathing red line. Uncertain records (several possible convents, contradictory dates) are dashed. Moving over or tapping a spiral shows her record: name before baptism where recorded, baptismal name, convent, dates, cause.

## 3. Situate

The Alps and northern Italy are the centre of the map. The Insubric Line and the Periadriatic Seam are drawn schematically: Bruneck, where Gambra*, Schiama* and Asue* lived, lies on it.

## 4. Narrate

The map is the starting point. The second layer, still to come, is how weather was used by the nuns and priests: as an explanation for the deaths ("climate") and as a means of discipline ("storm", "hitzig", "a gentle temperament").

## Sources and limits

- Source: Ute Küppers-Braun, *Gekauft im Namen des Herrn. Afrikanische Kindersklaven in europäischen Klöstern im 19. Jahrhundert*, Münster: Aschendorff 2021. Convents from Appendix 1, all entries from Appendix 2 (pp. 337–367). Transcribed from the book in November 2026; places geocoded by hand at town level.
- Records (places, names, dates, causes): historical, as recorded, many approximate. Durations are computed from arrival to death and approximate.
- Names: name before baptism where the source gives one, with all spellings, otherwise X*. Racist labels in the source are not reproduced. Some names (Bakhita, Mabruka) may themselves have been given during enslavement.
- Spirals, rotation, breathing: interpretive. Not observed weather.
- Breath: a cause of death is recorded for only 92 of 557 entries; 25 name lungs or breath, 22 more most likely mean the same.
- Coastline: Natural Earth (public domain), via the world-atlas package. Alps outline and fault lines: drawn by hand, schematic.
- The asterisk marks what the archive cannot hold: uncertain names, uncertain spellings, and categories imposed on them.
- The map cannot show discipline itself, only lifespans. The numbering in the source has gaps; the map shows the 557 recorded entries, not everyone.
- The page loads two fonts from Google Fonts; without internet it falls back to system fonts.
