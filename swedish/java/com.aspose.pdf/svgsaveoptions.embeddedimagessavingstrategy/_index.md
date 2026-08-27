---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Till en egenskap av sådan typ kan du tilldela en delegat skapad från en custom method som implementerar processing av external saving av image som extraherades från SVG skapad från PDF."
type: docs
weight: 4730
url: /sv/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Till en egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparning av en bild som extraherats från SVG skapad från PDF och som måste sparas som en extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. egen sparning till en ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter infogas i den genererade SVG:n istället för den ursprungliga förväntade sökvägen till bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i den anpassade koden, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo' i parametern. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
