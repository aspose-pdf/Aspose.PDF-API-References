---
title: "Delegat HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resursresourceFont eller Image som extraherades från PDF och måste sparas som en extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning, såsom sparande i ström eller på disk, göras i den anpassade koden och den anpassade koden måste returnera en sökväg eller någon annan sträng utan citattecken som därefter infogas i den genererade HTML:n istället för den ursprungliga förväntade sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för den här eller den där filen av någon anledning måste göras av konverterarens kod själv och inte i anpassad kod, vänligen sätt i den anpassade koden flaggan CustomProcessingCancelled för variabeln resourceSavingInfo‑parameter. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns."
type: docs
weight: 5860
url: /sv/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resurs (Font eller Image) som extraherades från PDF och måste sparas som en extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (som sparande i ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter infogas i den genererade HTML:n istället för den ursprungliga förväntade sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för den här eller den där filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'resourceSavingInfo'-parameter. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | representerar en uppsättning data för sparande av resurs |

### Returvärde

måste returnera en URL till den sparade resursen som kommer att användas under generering av HTML

### Se även

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


