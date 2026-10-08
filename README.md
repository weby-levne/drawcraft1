# DrawCraft

Bezplatný 2D/3D kreativní editor pro web, PC a mobil.

## Co je v této verzi
- 2D plátno s kreslením a gumou
- geometrické tvary
- výběr objektů pravým tlačítkem myši
- přesun a změna velikosti pomocí úchytů
- vlastnosti objektu (barva, průhlednost, rozměr)
- Undo / Redo
- PNG export
- barevné palety + vlastní barva
- responzivní UI pro dotyk
- základní 3D editor s rotací a primitivy
- vstupní bod pro 2D → 3D
- menu s reklamním placeholderem

## Spuštění
Otevři `index.html` v prohlížeči. Pro GitHub Pages stačí nahrát celý obsah repozitáře a Pages nastavit na větev `main` a složku `/ (root)`.

## Reklamy
Současný kód používá pouze vizuální placeholder „Krátká reklama“. Před zveřejněním je potřeba připojit skutečnou reklamní síť a ověřit její podmínky, věkové limity, souhlas s personalizací a pravidla pro mobilní aplikace.

## Další vývoj
1. skutečný objektový systém s přesnými 8 úchyty a rotací
2. vrstvy s pořadím, zamykáním a viditelností
3. ukládání projektů do IndexedDB
4. skutečný 3D renderer (WebGL/WebGPU)
5. robustní 2D → 3D extruze a rozpoznání obrysu
6. export SVG/3D formátů
7. PWA + Android/iOS wrapper
