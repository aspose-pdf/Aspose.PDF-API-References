---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern resurs (font eller bild) som extraherades från PDF och måste sparas."
type: docs
weight: 2150
url: /sv/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resurs (Font eller Bild) som extraherades från PDF och måste sparas som en extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. sparande i ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade HTML:n istället för den ursprungliga antagna sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'resourceSavingInfo' parameter. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Anropad metod |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Anropad metod
