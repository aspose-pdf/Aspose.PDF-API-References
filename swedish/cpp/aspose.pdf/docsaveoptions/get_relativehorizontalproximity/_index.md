---
title: "Aspose::Pdf::DocSaveOptions::get_RelativeHorizontalProximity metod"
linktitle: "get_RelativeHorizontalProximity"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocSaveOptions::get_RelativeHorizontalProximity metod. I PDF kan ord vara internt representerade med operatorer som skriver ut ord genom att oberoende skriva ut deras bokstäver eller stavelser. Så, för att upptäcka ord måste vi ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som måste behandlas som avstånd mellan ord under igenkänning av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst med denna bredd mellan bokstäver betyder att textelementen tillhör olika ord). Det''s normaliserat till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS!Det''s används endast i fall då käll‑PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så, i den stora majoriteten av fallen förändrar denna parameter ingenting i resultatdokumentet i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.pdf/docsaveoptions/get_relativehorizontalproximity/
---
## DocSaveOptions::get_RelativeHorizontalProximity method


I [Pdf](../../) kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord vid igenkänning av ord i käll-PDF. (Närvaro av ett tomt utrymme åtminstone med denna bredd mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast i fall då käll-PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i resultatdokumentet.

```cpp
float Aspose::Pdf::DocSaveOptions::get_RelativeHorizontalProximity() const
```

## Se även

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
