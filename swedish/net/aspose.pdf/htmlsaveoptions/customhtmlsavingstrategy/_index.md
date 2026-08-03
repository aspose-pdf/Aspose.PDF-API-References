---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "HtmlSaveOptions-fält. Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML‑sida för att exakt markupHTML utan externa länkade filer, om sådana skapades under konverteringen. I sådana fall kan bearbetning såsom sparande av HTML‑sidor i ström eller på disk göras i den anpassade koden. Alla nödvändiga åtgärder för att spara HTML‑sidan måste då utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller annat fall av någon anledning måste utföras av konverterarens kod själv och inte i anpassad kod, ställ in flaggan CustomProcessingCancelled i variabeln htmlSavingInfo‑parametrar i den anpassade koden; den kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad kod fanns för bearbetning."
type: docs
weight: 270
url: /sv/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela den här egenskapen en delegat som skapats från en anpassad metod som implementerar bearbetning av en HTML‑sida (för att vara exakt – markup‑HTML, utan externa länkade filer om några) som skapades under konverteringen. I sådant fall kan bearbetning (t.ex. sparande av sidans HTML i en ström eller på disk) göras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML‑sidan utföras i den medföljande metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad kod fanns för bearbetning.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Se även

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


