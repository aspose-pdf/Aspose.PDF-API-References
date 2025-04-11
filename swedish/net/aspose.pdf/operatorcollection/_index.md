---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OperatorCollection klass. Klassen representerar en samling av operatörer
type: docs
weight: 7080
url: /sv/net/aspose.pdf/operatorcollection/
---
## OperatorCollection klass

Klassen representerar en samling av operatörer

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Hämtar antalet operatörer i samlingen. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indikerar om samlingen är begränsad till snabb textutvinning |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Hämtar operatören efter dess index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Accepterar IOperatorSelector besöksobjekt för att bearbeta operatörer. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Lägger till alla operatörer från en annan samling till samlingen. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Lägger till en ny operatör i samlingen. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Lägger till operatörer i slutet av innehållets operatörer. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska orsaka en uppdatering av innehållet. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Tar bort alla operatörer från listan. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Returnerar sant om samlingen innehåller den angivna operatören. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Kopierar operatörer till operatörslistan. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Tar bort operatörer från samlingen. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Tar bort operatören från samlingen. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Tar bort operatörer från samlingen. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Utför applikationsdefinierade uppgifter kopplade till att frigöra, släppa eller återställa icke-hanterade resurser. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Returnerar en uppräkning för samlingen |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Infogar operatörer på den angivna positionen. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Infogar operatören i samlingen. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Infogar operatörer på den angivna positionen. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Tar bort operatören från samlingen. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Ersätter operatörer i samlingen med andra operatörer. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Återupptar dokumentuppdateringen. Uppdaterar innehållsströmmen om det finns några utestående ändringar. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Återupptar dokumentuppdateringen. Uppdaterar innehållsströmmen om det finns några utestående ändringar. Markerar alla operatörer som "ändrade" om ogiltig parameter är sann. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Suppresserar uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Returnerar textrepresentationen av operatören. |

### Se Även

* klass [BaseOperatorCollection](../baseoperatorcollection/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)