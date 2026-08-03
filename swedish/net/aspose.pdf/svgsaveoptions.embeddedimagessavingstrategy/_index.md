---
title: "Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Till egenskap av sådan typ kan du tilldela en delegate skapad från en anpassad metod som implementerar bearbetning av extern sparning av bild som extraherats från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning som egen sparning till ström eller på disk göras i den anpassade koden och den anpassade koden måste returnera en sökväg eller någon annan sträng utan citattecken som därefter införlivas i den genererade SVG:n istället för den ursprungliga antagna sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för sparning av bilden utföras i den levererade metodens kod eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv och inte i anpassad kod, ställ i den anpassade koden flaggan CustomProcessingCancelled i variabeln imageSavingInfo‑parametrar. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns. Representerar information om sparad bild som kan användas i anpassad kod och måste returnera en sträng som representerar URL för bilden som kommer att placeras i SVG."
type: docs
weight: 10420
url: /sv/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

Till egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparning av en bild som extraherades från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (som egen sparning till ström eller till disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade SVG:n istället för den ursprungliga antagna sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, ange i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo'-parametern. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om ingen extern anpassad kod fanns. representerar information om sparad bild som kan användas i anpassad kod måste returnera en sträng som representerar URL-adressen till bilden som kommer att placeras i SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Se även

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


