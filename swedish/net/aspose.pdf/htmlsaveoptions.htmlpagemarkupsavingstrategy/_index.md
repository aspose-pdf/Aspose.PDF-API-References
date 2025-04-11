---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Resultatet av konverteringen kan innehålla en eller flera HTML-sidor som också kan referera till externa filer som bilder eller typsnitt. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av den erhållna HTML-sidan som skapades under konverteringen. I sådana fall kan bearbetning som att spara i ström eller på disk göras i den anpassade koden. I sådana fall måste alla nödvändiga åtgärder för att spara HTML-sidornas markup vidtas i koden för den tillhandahållna metoden eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv och inte i den anpassade koden, vänligen ställ in flaggan CustomProcessingCancelled i den anpassade kodens htmlSavingInfo-parameter, det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv på samma sätt som om det inte fanns någon extern anpassad sparande kod.
type: docs
weight: 5680
url: /sv/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
| --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | representerar data som kan användas för att spara eller bearbeta den tillhandahållna HTML-sidan |

### Se Även

* klass [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)