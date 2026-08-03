---
title: "DocSaveOptions.RelativeHorizontalProximity"
second_title: "Aspose.PDF för .NET API‑referens"
description: "DocSaveOptions.egenskap. I PDF kan ord internt representeras med operatorer som skriver ut ord genom att oberoende skriva ut deras bokstäver eller stavelser. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelementens bokstäver/stavelser som måste behandlas som avstånd mellan ord under igenkänning av ord i käll‑PDF. Förekomst av ett tomt utrymme åtminstone med denna bredd mellan bokstäver betyder att text‑elementen tillhör olika ord. Den är normaliserad till teckenstorlek 1,0 vilket motsvarar 100 % av den antagna ordens teckenstorlek. OBS! Den används endast i fall när käll‑PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter inget i det resulterande dokumentet."
type: docs
weight: 120
url: /sv/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity property

I Pdf kan ord internt representeras med operators som skriver ut ord genom att oberoende skriva ut deras letters eller syllables. Så för att upptäcka ord måste vi ibland identifiera grupper av oberoende chars som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (letters, syllables) som ska behandlas som avstånd mellan ord under identifiering av ord i käll-Pdf. (Närvaro av ett tomt utrymme minst lika brett som detta mellan letters betyder att textelementen tillhör olika ord). Den är normaliserad till font size – 1,0 betyder 100 % av det antagna ordets font size. ATTENTION! Den används endast i fall då käll-Pdf innehåller specifika sällan använda fonts för vilka det optimala värdet inte kan beräknas från font. Så i de allra flesta fall förändrar denna parameter inget i det resulterande dokumentet.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Se även

* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


