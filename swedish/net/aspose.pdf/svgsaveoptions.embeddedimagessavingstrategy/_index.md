---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Till egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparande av bild som extraherades från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådana fall kan bearbetning (som egen sparande i ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera sökväg (eller någon annan sträng utan citattecken) som senare kommer att införlivas i den genererade SVG istället för den ursprungliga antagna sökvägen till den bildresursen. I sådana fall måste alla nödvändiga åtgärder för att spara bilden vidtas i koden för den tillhandahållna metoden, eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den fil av någon anledning måste göras av konverterarens kod själv, inte i den anpassade koden, vänligen ställ in i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo' parameter. Det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod. representerar information om sparad bild som kan användas i den anpassade koden måste returnera sträng som representerar URL för bilden som kommer att sättas in i SVG
type: docs
weight: 10240
url: /sv/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegat

Till egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparande av bild som extraherades från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådana fall kan bearbetning (som egen sparande i ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera sökväg (eller någon annan sträng utan citattecken) som senare kommer att införlivas i den genererade SVG istället för den ursprungliga antagna sökvägen till den bildresursen. I sådana fall måste alla nödvändiga åtgärder för att spara bilden vidtas i koden för den tillhandahållna metoden, eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den fil av någon anledning måste göras av konverterarens kod själv, inte i den anpassade koden, vänligen ställ in i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo' parameter. Det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod. representerar information om sparad bild som kan användas i den anpassade koden måste returnera sträng som representerar URL för bilden som kommer att sättas in i SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Se Även

* klass [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* klass [SvgSaveOptions](../svgsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)