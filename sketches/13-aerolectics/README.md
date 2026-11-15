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

An interpretive map, draft of 15 November, made to ask questions rather than to answer them. Every girl* and young woman* in the list is a storm at her convent town, all the same size: the map names and remembers, it does not measure. A point means her death is recorded; a storm that keeps turning means it is not. Names appear when you zoom in close. At least 643 more storms drift without name, place or date: Olivieri and Verri bought more than 1,200 girls (p. 302), the list holds 557.

Around them, the climate they were exposed to: the 171 convents named in Appendix 1, lines where convents crowd together (a density of institutions, not of girls), and "voices of the climate": what nuns, bishops and priests wrote about climate, storms and thunder, drawn as weather fronts at their places. The storm track runs from capture in Sudan and Ethiopia via Cairo and Alexandria to every storm; it is interpretation, not recorded routes. Layers can be switched on and off to see them against each other.

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
- Climate layer: convents and orders from Appendix 1; density lines computed from convent locations only (kernel density, schematic, no units). Quotes from pp. 86, 92, 106, 107, 114, 118, 131, 140, 165, 200, 269; English renderings are translations. Positions of the drifting storms are random by design.
- Coastline: Natural Earth (public domain), via the world-atlas package. Alps outline and fault lines: drawn by hand, schematic.
- The asterisk marks what the archive cannot hold: uncertain names, uncertain spellings, and categories imposed on them.
- The map cannot show discipline itself, only lifespans. The numbering in the source has gaps; the map shows the 557 recorded entries, not everyone.
- The page loads two fonts from Google Fonts; without internet it falls back to system fonts.
