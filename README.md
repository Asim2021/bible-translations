# Bible Translations

This repository contains 48 Bible translations in JSON format, stored in [`formats/json`](formats/json).

## Available Translations

- [AKJV](formats/json/AKJV.json)
- [Alb](formats/json/Alb.json)
- [ArmEastern](formats/json/ArmEastern.json)
- [ASV](formats/json/ASV.json)
- [BBE](formats/json/BBE.json)
- [BSB](formats/json/BSB.json)
- [CebPinadayag](formats/json/CebPinadayag.json)
- [ChiSB](formats/json/ChiSB.json)
- [ChiUn](formats/json/ChiUn.json)
- [CroSaric](formats/json/CroSaric.json)
- [CzeBKR](formats/json/CzeBKR.json)
- [DaOT1871NT1907](formats/json/DaOT1871NT1907.json)
- [Darby](formats/json/Darby.json)
- [DRC](formats/json/DRC.json)
- [DutSVV](formats/json/DutSVV.json)
- [FinPR](formats/json/FinPR.json)
- [FreBBB](formats/json/FreBBB.json)
- [FreCrampon](formats/json/FreCrampon.json)
- [FreSynodale1921](formats/json/FreSynodale1921.json)
- [Geneva1599](formats/json/Geneva1599.json)
- [GerBoLut](formats/json/GerBoLut.json)
- [GerElb1905](formats/json/GerElb1905.json)
- [GerMenge](formats/json/GerMenge.json)
- [GerSch](formats/json/GerSch.json)
- [GreVamvas](formats/json/GreVamvas.json)
- [Haitian](formats/json/Haitian.json)
- [HebModern](formats/json/HebModern.json)
- [JapBungo](formats/json/JapBungo.json)
- [JapKougo](formats/json/JapKougo.json)
- [KorHKJV](formats/json/KorHKJV.json)
- [KorRV](formats/json/KorRV.json)
- [Mal1910](formats/json/Mal1910.json)
- [Norsk](formats/json/Norsk.json)
- [PolGdanska](formats/json/PolGdanska.json)
- [PorBLivre](formats/json/PorBLivre.json)
- [PorNVA](formats/json/PorNVA.json)
- [RusSynodal](formats/json/RusSynodal.json)
- [SpaPlatense](formats/json/SpaPlatense.json)
- [SpaRV](formats/json/SpaRV.json)
- [SpaRV1865](formats/json/SpaRV1865.json)
- [Swe1917](formats/json/Swe1917.json)
- [TagAngBiblia](formats/json/TagAngBiblia.json)
- [ThaiKJV](formats/json/ThaiKJV.json)
- [UkrOgienko](formats/json/UkrOgienko.json)
- [Viet](formats/json/Viet.json)
- [Vulgate](formats/json/Vulgate.json)
- [VulgClementine](formats/json/VulgClementine.json)
- [YLT](formats/json/YLT.json)

## JSON Structure

Each file contains a translation title and a hierarchy of books, chapters, and verses. Each verse includes its number and text.

```json
{
  "translation": "AKJV: American King James Version",
  "books": [
    {
      "name": "Genesis",
      "chapters": [
        {
          "chapter": 1,
          "verses": [
            {
              "verse": 1,
              "text": "In the beginning God created the heaven and the earth."
            }
          ]
        }
      ]
    }
  ]
}
```

See [LICENSE](LICENSE) for the repository license.