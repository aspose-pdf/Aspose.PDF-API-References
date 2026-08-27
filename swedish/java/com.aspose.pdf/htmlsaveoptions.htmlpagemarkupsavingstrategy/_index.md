---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat skapad från."
type: docs
weight: 2110
url: /sv/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Resultatet av konverteringen kan innehålla en eller flera HTML-sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av den erhållna HTML-sidan (HTML själv) som skapades under konverteringen. I sådant fall kan bearbetning (som att spara i en ström eller på disk) göras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML-sidans markup utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad sparkod fanns.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Intern beginInvoke‑metod |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Intern endInvoke‑metod |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Anropad metod |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Intern beginInvoke‑metod

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Intern endInvoke‑metod

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Anropad metod
