# Ako nahrať tento web na GitHub Pages

Toto je hotová statická stránka, jeden súbor index.html so všetkým vnútri, a priečinok images. Netreba žiadny build, žiadny Jekyll.

## Nahranie súborov, bez príkazového riadku

1. Otvor svoj repozitár na GitHube.
2. Klikni Add file, potom Upload files.
3. Pretiahni tam index.html, README.md, favicon.svg, favicon-32.png, apple-touch-icon.png a celý priečinok images.
4. Dole klikni Commit changes.

## Zapnutie GitHub Pages

1. V repozitári choď do Settings.
2. V ľavom menu klikni Pages.
3. Pri Source vyber Deploy from a branch.
4. Pri Branch vyber main a priečinok root.
5. Klikni Save.
6. Počkaj jednu až dve minúty, hore sa objaví odkaz na živú stránku.

## Čo sa zmenilo v tomto kole

Tagy v ľavom stĺpci, Researching, Speaking, Writing, Coordinating, Exhibiting, Photographing, sú teraz klikateľné. Kliknutím na jeden alebo viac naraz sa v sekcii Research zobrazia len položky s daným typom, aj s príslušnými rokmi, ostatné sa skryjú. Opätovným kliknutím na aktívny tag ho vypneš, keď nie je aktívny žiadny tag, vidno všetko. Aktívny tag je zvýraznený tmavočervenou farbou. Táto funkcia je zatiaľ len na počítačovom zobrazení, na mobile sa tagy v bočnom paneli momentálne nezobrazujú vôbec, rovnako ako predtým, takže tam ani filter nie je k dispozícii. Ak by si ho chcela aj na mobile, viem to doplniť.

Photographing sa medzi výskumnými položkami nikde nenachádza, keďže žiadna z nich nie je označená ako fotografovanie, takže po jeho zapnutí sekcia Research zostane prázdna a zostane viditeľná len fotografická sekcia nižšie. Ak by si chcela iné správanie, napríklad aby Photographing namiesto filtrovania len odskrolovalo na fotografie, daj vedieť.

Popisky fotiek v tretej sérii už neobsahujú Včelí kRaj, teraz odkazujú na aktuálny názov série, Soil, care and repair in spatial practice for a more than human world.

Akcentová farba je teraz #3C2640, viac fialová, menej slivková. Keďže je to jedna premenná na začiatku súboru, --accent, prejaví sa všade naraz, nadpisy, aktívne tagy, odkazy aj orámovanie pri klávesovom prechádzaní.

Pribudol favicon, malá ikonka v tejto fialovej s bielym G, ktorá sa zobrazuje v karte prehliadača a pri pridaní stránky na plochu telefónu. Súbory favicon.svg, favicon-32.png a apple-touch-icon.png treba nahrať do repozitára na rovnakú úroveň ako index.html, teda priamo do koreňa, nie do priečinka images.

## Chýbajúci súbor

V sekcii Research, pri položke Czech and Slovak Spatial Practice for 99% z roku 2026, stránka odkazuje na images/research/beyond_architecture.jpg. Tento súbor nemám, na mieste obrázka bude prázdno, kým ho nenahráš do priečinka images/research.

## Ak niečo iné nesedí

Napíš mi presne ktorá položka, poviem ti presne kde to v súbore zmeniť, alebo to rovno upravím ja.
