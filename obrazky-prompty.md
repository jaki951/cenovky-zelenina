# Obrázky pre cenovky – zoznam produktov a prompt

Vygenerované zo `products.json` (63 produktov, poradie ako na cenovkách).

## Prompt

Mení sa **len** `{SUBJECT}` – zvyšok nechaj rovnaký, inak sa štýl medzi obrázkami rozíde.

```
Flat colour illustration of a single {SUBJECT}, centered, square composition, generous empty margin around the subject, pure white background, bold black outlines, limited flat colour palette, vintage farmers-market style, no text, no labels, no watermark, no shadows
```

## Produkty

| # | Názov na cenovke | `{SUBJECT}` do promptu | Názov súboru |
|---|---|---|---|
| 1 | Mrkva | carrot | `mrkva.png` |
| 2 | Petržlen | parsley root (Hamburg parsley), pale beige root with green leafy top | `petrzlen.png` |
| 3 | Zemiaky | potatoes | `zemiaky.png` |
| 4 | Zemiaky 2,5kg | potatoes | `zemiaky-2-5kg.png` |
| 5 | Banány | bunch of bananas | `banany.png` |
| 6 | Hrušky | pears | `hrusky.png` |
| 7 | Kiwi | kiwi fruit, one whole and one halved | `kiwi.png` |
| 8 | Pomaranče | oranges | `pomarance.png` |
| 9 | Cesnak | garlic bulb | `cesnak.png` |
| 10 | Zeler | celeriac (celery root bulb) | `zeler.png` |
| 11 | Pór | leek | `por.png` |
| 12 | Paradajky veľké | large tomato | `paradajky-velke.png` |
| 13 | Hrozno biele | bunch of green grapes | `hrozno-biele.png` |
| 14 | Hrozno červené | bunch of red grapes | `hrozno-cervene.png` |
| 15 | Mandarinky | mandarin oranges | `mandarinky.png` |
| 16 | Mandarinky veľké | large mandarin oranges | `mandarinky-velke.png` |
| 17 | Kapusta biela | white cabbage head | `kapusta-biela.png` |
| 18 | Kapusta červená | red cabbage head | `kapusta-cervena.png` |
| 19 | Parika farebná | colourful bell peppers (red, yellow, green) | `parika-farebna.png` |
| 20 | Paradajky kríčkové | tomatoes on the vine | `paradajky-krickove.png` |
| 21 | Jablká červené | red apple | `jablka-cervene.png` |
| 22 | Jablká zelené | green apple | `jablka-zelene.png` |
| 23 | Grep | grapefruit, one whole and one halved | `grep.png` |
| 24 | Avocado | avocado, one whole and one halved with stone | `avocado.png` |
| 25 | Kel | savoy cabbage head | `kel.png` |
| 26 | Karfiol | cauliflower | `karfiol.png` |
| 27 | Paprika biela | pale yellow-white sweet pepper (Hungarian wax pepper) | `paprika-biela.png` |
| 28 | Uhorky | cucumber | `uhorky.png` |
| 29 | Nektarinky | nectarines | `nektarinky.png` |
| 30 | Citróny | lemons | `citrony.png` |
| 31 | Brokolica | broccoli | `brokolica.png` |
| 32 | Cuketa | courgette (zucchini) | `cuketa.png` |
| 33 | Cibula červená | red onion | `cibula-cervena.png` |
| 34 | Mrkva viazan. | bunch of carrots with green tops | `mrkva-viazan.png` |
| 35 | Kaleráb | kohlrabi with leaves | `kalerab.png` |
| 36 | Zázvor | ginger root | `zazvor.png` |
| 37 | Kukurica | corn cob (sweetcorn) with husk | `kukurica.png` |
| 38 | Melón červený | watermelon, one wedge and one whole | `melon-cerveny.png` |
| 39 | Chren | horseradish root | `chren.png` |
| 40 | Gaštany | chestnuts | `gastany.png` |
| 41 | Petržlen viazan. | bunch of parsley roots with leafy tops | `petrzlen-viazan.png` |
| 42 | Červená repa | beetroot with stems | `cervena-repa.png` |
| 43 | Pekingská kapusta | napa cabbage (Chinese cabbage) | `pekingska-kapusta.png` |
| 44 | Šalát ľadový | iceberg lettuce head | `salat-ladovy.png` |
| 45 | Melón žltý | honeydew melon, one wedge and one whole | `melon-zlty.png` |
| 46 | Broskyne | peaches | `broskyne.png` |
| 47 | Hrach | green peas in pods | `hrach.png` |
| 48 | Jahody | strawberries | `jahody.png` |
| 49 | Hokhaido | hokkaido pumpkin (red kuri squash) | `hokhaido.png` |
| 50 | Granátové jablko | pomegranate, one whole and one halved | `granatove-jablko.png` |
| 51 | Cibuľka | bunch of spring onions | `cibulka.png` |
| 52 | Reďkovka | bunch of red radishes | `redkovka.png` |
| 53 | Marhule | apricots | `marhule.png` |
| 54 | Slivky | plums | `slivky.png` |
| 55 | Kaki | persimmon (kaki fruit) | `kaki.png` |
| 56 | Limetka | limes | `limetka.png` |
| 57 | Pitahya | dragon fruit (pitaya), one whole and one halved | `pitahya.png` |
| 58 | Čerešne | cherries with stems | `ceresne.png` |
| 59 | Cibuľa | yellow onion | `cibula.png` |
| 60 | Pomelo | pomelo citrus fruit | `pomelo.png` |
| 61 | Ananás | pineapple | `ananas.png` |
| 62 | Mango | mango, one whole and one halved | `mango.png` |
| 63 | Kokos | coconut, one whole and one halved | `kokos.png` |

## Poznámky

- **Neprekladaj názvy sám** – `Petržlen` je koreň (nie vňať), `Zeler` je buľva, `Kel` je savoy cabbage, `Kaleráb` kohlrabi, `Hokhaido` tekvica, `Pitahya` dračie ovocie. Pri zlom preklade dostaneš iný produkt.
- `Zemiaky` a `Zemiaky 2,5kg` sú ten istý obrázok, rovnako `Mandarinky` / `Mandarinky veľké` a `Paradajky veľké` / `Paradajky kríčkové` sa líšia len detailom – stačí 60 obrázkov na 63 cenoviek.
- Obrázok **ukladaj priamo** (pravý klik → uložiť), nie screenshotom – terajšie obrázky v tabuľke sú screenshoty okien a preto sú nepoužiteľné.
- Rozlíšenie 1024×1024 stačí; kruh na cenovke má 39 mm ≈ 460 px pri 300 dpi.
