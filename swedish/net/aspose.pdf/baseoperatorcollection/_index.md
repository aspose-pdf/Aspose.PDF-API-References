---
title: "Klassen BaseOperatorCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.BaseOperatorCollection-klass. Representerar basklass för operator-samling."
type: docs
weight: 2940
url: /sv/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

Representerar basklass för operator-samling.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Hämtar antalet operatorer i samlingen. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indikerar om samlingen är begränsad till snabb textutvinning |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Returnerar true om samlingen är skrivskyddad. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Hämtar operatorn efter dess index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Lägger till en ny operator i samlingen. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska utlösa en innehållsuppdatering. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Rensar samlingen. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Kontrollerar om operator finns i samlingen. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Kopierar operatorer till operatorlistan. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Returnerar en enumerator för samlingen |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Infogar operatorn i samlingen. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Tar bort operator från samlingen. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns väntande ändringar. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |

### Se även

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


