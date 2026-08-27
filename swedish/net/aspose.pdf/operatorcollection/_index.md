---
title: "Klass OperatorCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.OperatorCollection-klass. Klassen representerar en samling av operatorer"
type: docs
weight: 7220
url: /sv/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

Klassen representerar en samling av operatorer.

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Hämtar antalet operatorer i samlingen. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indikerar om samlingen är begränsad till snabb textutvinning |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Hämtar operatorn efter dess index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Accepterar IOperatorSelector‑besökareobjekt för att bearbeta operatorer. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Lägger till alla operatorer från en annan samling i samlingen. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Lägger till en ny operator i samlingen. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Lägg till operatorer i slutet av innehållsoperatorerna. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska utlösa en innehållsuppdatering. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Tar bort alla operatorer från listan. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Returnerar true om samlingen innehåller den angivna operatorn. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Kopierar operatorer till operatorlistan. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Raderar operatorer från samlingen. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Raderar operatorn från samlingen. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Raderar operatorer från samlingen. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till frigöring, släppande eller återställning av ohanterade resurser. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Returnerar en enumerator för samlingen |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Infoga operatorer på den angivna positionen. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Infogar operatorn i samlingen. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Infoga operatorer på den angivna positionen. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Ta bort operatorn från samlingen. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Ersätt operatorer i samlingen med andra operatorer. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns väntande ändringar. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns väntande ändringar. Markerar alla operatorer som "changed" om parametern invalidate är true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Returnerar textrepresentation av operatorn. |

### Se även

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


