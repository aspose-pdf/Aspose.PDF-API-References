---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions-fält. Resultatet av konverteringen kan innehålla en eller flera HTML-sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML-sida (för att vara exakt - markup-HTML, utan externa länkade filer om några) som skapades under konverteringen. I sådana fall kan bearbetning (som att spara HTML-sidan i ström eller på disk) göras i den anpassade koden. I sådana fall måste alla nödvändiga åtgärder för att spara HTML-sidan vidtas i koden för den tillhandahållna metoden, eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i den anpassade koden, vänligen ställ in flaggan 'CustomProcessingCancelled' i den anpassade kodens variabel 'htmlSavingInfo': det kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv på samma sätt som om det inte fanns någon extern anpassad kod för bearbetning.
type: docs
weight: 270
url: /sv/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy-fält

Resultatet av konverteringen kan innehålla en eller flera HTML-sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML-sida (för att vara exakt - markup-HTML, utan externa länkade filer om några) som skapades under konverteringen. I sådana fall kan bearbetning (som att spara HTML-sidan i ström eller på disk) göras i den anpassade koden. I sådana fall måste alla nödvändiga åtgärder för att spara HTML-sidan vidtas i koden för den tillhandahållna metoden, eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i den anpassade koden, vänligen ställ in flaggan 'CustomProcessingCancelled' i den anpassade kodens variabel 'htmlSavingInfo': det kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv på samma sätt som om det inte fanns någon extern anpassad kod för bearbetning.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Se Även

* delegat [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* klass [HtmlSaveOptions](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)