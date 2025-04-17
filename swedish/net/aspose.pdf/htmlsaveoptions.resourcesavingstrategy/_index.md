---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Till denna egendom kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern resurs, font eller bild som har extraherats från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådana fall kan bearbetning som att spara i ström eller på disk göras i den anpassade koden och den anpassade koden måste returnera sökväg eller någon annan sträng utan citattecken som senare kommer att införlivas i den genererade HTMLen istället för den ursprungliga avsedda sökvägen till den bildresursen. I sådana fall måste alla nödvändiga åtgärder för att spara bilden vidtas i koden för den tillhandahållna metoden eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den fil av någon anledning måste göras av konverterarens kod själv och inte i den anpassade koden, vänligen ställ in i den anpassade koden flaggan CustomProcessingCancelled i resursSparandeInfo-parametervariabeln. Det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod.
type: docs
weight: 5730
url: /sv/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
| --- | --- |
| resourceSavingInfo | ResourceSavingInfo | representerar en uppsättning data för sparande av resurs |

### Returvärde

måste returnera URL till sparad resurs som kommer att användas under generation av HTML

### Se Även

* klass [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)