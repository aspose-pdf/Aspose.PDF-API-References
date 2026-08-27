---
title: "Delegat HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor som också kan referera till externa filer som bilder eller teckensnitt. Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av den HTML‑sida som skapades under konverteringen. I så fall kan bearbetning såsom sparande till ström eller disk göras i den anpassade koden. Alla nödvändiga åtgärder för att spara HTML‑sidornas markup måste då utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller annat fall av någon anledning måste göras av konverterarens kod själv och inte i anpassad kod, sätt i den anpassade koden flaggan CustomProcessingCancelled i variabeln htmlSavingInfo‑parametrar. Detta signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad sparkod fanns."
type: docs
weight: 5810
url: /sv/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat som skapats från en anpassad metod som implementerar bearbetning av den erhållna HTML‑sidan (HTML själv) som skapades under konverteringen. I sådant fall kan bearbetning (t.ex. sparande i ström eller på disk) göras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML‑sidans markup utföras i den levererade metodens kod, eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om det inte fanns någon extern anpassad sparkod.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | representerar data som kan användas för att spara eller bearbeta den levererade HTML‑sidan |

### Se även

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


