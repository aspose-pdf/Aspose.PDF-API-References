---
title: "Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity metod"
linktitle: "set_RelativeHorizontalProximity"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity metod. I PDF kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord vid igenkänning av ord i käll-PDF. (Närvaro av ett tomt utrymme åtminstone med denna bredd mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast i fall då käll-PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i resultatdokumentet i C++."
type: docs
weight: 2400
url: /sv/cpp/aspose.pdf/docsaveoptions/set_relativehorizontalproximity/
---
## DocSaveOptions::set_RelativeHorizontalProximity method


I [Pdf](../../) kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord vid igenkänning av ord i käll-PDF. (Närvaro av ett tomt utrymme åtminstone med denna bredd mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast i fall då käll-PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i resultatdokumentet.

```cpp
void Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity(float value)
```

## Se även

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
