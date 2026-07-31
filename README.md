# Ako nahrať tento web na GitHub Pages

Toto je hotová statická stránka, tri súbory a priečinok images. Netreba žiadny build, žiadny Jekyll, len tieto súbory nahrať do repozitára.

## Nahranie súborov (bez príkazového riadku)

1. Otvor svoj nový repozitár na GitHube.
2. Klikni na tlačidlo Add file a potom Upload files.
3. Pretiahni tam všetky súbory a priečinky z tohto balíčka, teda index.html, style.css, .nojekyll a celý priečinok images so všetkým vnútri.
4. Dole klikni Commit changes.

## Zapnutie GitHub Pages

1. V repozitári choď do Settings.
2. V ľavom menu klikni Pages.
3. Pri Source vyber Deploy from a branch.
4. Pri Branch vyber main a priečinok root.
5. Klikni Save.
6. Počkaj jednu až dve minúty a hore sa objaví odkaz na živú stránku, niečo ako tvojemeno.github.io/nazovrepozitara.

Ak sa .nojekyll súbor pri nahrávaní nezobrazí (niektoré prehliadače skrývajú súbory začínajúce bodkou), pokojne ho vynechaj, stránka bude fungovať aj bez neho.

## Čo ešte doplniť

Fotografická sekcia má teraz tri minisérie a jednu úvodnú fotku nad textom.

Úvodná fotka, Run, jelene utekajúce cez oplotený pozemok pri Bratislave, je hotová, súbor je images/run.jpg. Umiestnila som ju hore ako mostík medzi výskumom a fotografiou, keďže sa priamo týka viac ako ľudských hlasov v priestore. Ak by si ju radšej videla inde, napríklad priamo v sérii Včelí kRaj, pokojne ju presuň, stačí presunúť blok figure class hero plate v index.html.

Prvá séria, Sisters, Daughters, Mothers, je hotová, fotky sa dočasne načítavajú priamo z Analog Sparks Awards.

Druhá séria, Planet Panelak, je tiež hotová, všetkých trinásť fotiek sa načítava priamo z tvojho profilu na Life Frameri.

Pri oboch týchto sériách odporúčam fotky neskôr stiahnuť a nahrať do vlastných priečinkov images/series-01 a images/series-02, aby stránka nezávisela od cudzích serverov, ktoré raz môžu zmeniť adresu alebo obsah zmazať.

Tretia séria, Včelí kRaj, je teraz tiež hotová, jedenásť fotiek z tvojho Canva exportu je už uložených priamo v priečinku images/series-03 a v stránke, takže od žiadneho cudzieho servera nezávisí. Ak by si chcela použiť len časť z jedenástich fotiek, stačí v index.html vymazať príslušné bloky s tagom a v sekcii Včelí kRaj a upraviť číslovanie pri fnum, napríklad z 11/11 na 08/08.

Text v research sekcii je prevzatý z tvojho portfólia, len preusporiadaný. Kľudne uprav čokoľvek priamo v index.html, je to obyčajný text medzi značkami.

## Poznámka k opencallu

Over si, či daný opencall prijíma odkaz na web, alebo vyžaduje priamo súbor, napríklad PDF alebo JPG nahraté do ich formulára. Ak vyžaduje súbor, tvoje pôvodné portfólio vo Worde môžeš poslať rovno tak, ako je, a táto stránka ti zostane ako trvalé portfólio nezávisle od uzávierky.
