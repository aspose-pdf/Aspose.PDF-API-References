---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection klass. Representerar basklass för operator samling
type: docs
weight: 2830
url: /sv/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection klass

Representerar basklass för operator samling.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Hämtar antalet operatörer i samlingen. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indikerar om samlingen är begränsad till snabb textutvinning |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Returnerar sant om samlingen är skrivskyddad. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Hämtar operatör efter dess index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Lägger till ny operatör i samlingen. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Avbryter senaste uppdatering. Denna metod kan anropas när ändringen inte ska orsaka innehållsuppdatering. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Rensar samlingen. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Kontrollerar om operatören finns i samlingen. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Kopierar operatörer till operatörslistan. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Returnerar enumerator för samlingen |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Infogar operatör i samlingen. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Tar bort operatör från samlingen. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några utestående ändringar. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Suppresserar uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |

### Se Även

* klass [Operator](../operator/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)