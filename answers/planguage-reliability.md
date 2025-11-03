# Gæðakrafa (PLanguage): Áreiðanleiki

> Þetta skjal útfærir kröfuna fyrir Áreiðanleika (Reliability) með aðferðinni **P-Language** samkvæmt Wiegers & Beatty (kafli 14).

---

## Merkimiði (TAG)
`Reliability.Uptime.CoreFunctionality`

---

## Tilgangur / Ásetningur (AMBITION)
Að tryggja að kjarnavirkni kerfisins (aðgangur að lyfjagjöf og bjargráðum) sé alltaf tiltæk fyrir starfsfólk, þar sem truflanir geta haft alvarlegar afleiðingar fyrir öryggi þjónustunotenda.

---

## Mælikvarði (SCALE)
Hlutfallstími (uppitími) yfir einn almanaksmánuð sem kjarnavirkni er aðgengileg.

---

## Mælir / Mæliaðferð (METER)
Mælt með sjálfvirku vöktunartóli sem reynir innskráningu og aðgang að lyfjagjöf á 1 mínútu fresti. Niðritími hefst þegar tvær mælingar í röð mistakast og lýkur þegar ein mæling tekst.

---

## Markmið (GOAL)
Uppitími skal vera **99.9%** (leyfilegt niðurbrot samtals 43.8 mínútur á mánuði).
*(Hagsmunaaðili: Umsjónaraðili þjónustu)*

---

## Æskilegt (STRETCH)
Uppitími skal vera **99.95%** (leyfilegt niðurbrot samtals 21.9 mínútur á mánuði).

---

## Ósk (WISH)
Uppitími skal vera **99.99%** (leyfilegt niðurbrot samtals 4.4 mínútur á mánuði).

---

## Grunnkerfi (BASE PLATFORM)
Kerfið keyrt í Azure (Vestur-Evrópa) með venjulegu álagi (50-200 samtímanotendur).
