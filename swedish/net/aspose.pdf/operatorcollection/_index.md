---
title: OperatorCollection
second_title: Aspose.PDF för .NET API Referens
description: Klass representerar samling av operatorer
type: docs
weight: 4860
url: /sv/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

Klass representerar samling av operatorer

```csharp
public class OperatorCollection : BaseOperatorCollection
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count) { get; } | Får antalet operatörer i samlingen. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode) { get; } | Indikerar att insamlingen av väder är begränsad till snabb textextrahering |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly) { get; } | Får ett värde som indikerar om samlingen är skrivskyddad. |
| override [Item](../../aspose.pdf/operatorcollection/item) { get; set; } | Hämtar operator genom dess index. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept)(IOperatorSelector) | Accepterar IOperatorSelector-besökarobjekt för processoperatörer. |
| [Add](../../aspose.pdf/operatorcollection/add#add_2)(ICollection&lt;Operator&gt;) | Lägger till alla operatörer från andra samlingar i samlingen. |
| override [Add](../../aspose.pdf/operatorcollection/add#add)(Operator) | Lägger till ny operatör i samlingen. |
| [Add](../../aspose.pdf/operatorcollection/add#add_1)(Operator[]) | Lägg till operatorer i slutet av innehållsoperatorerna. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate)() | Avbryter senaste uppdatering. Den här metoden kan anropas när ändringen inte bör öka innehållsuppdateringen. |
| override [Clear](../../aspose.pdf/operatorcollection/clear)() | Tar bort alla operatorer från listan. |
| override [Contains](../../aspose.pdf/operatorcollection/contains)(Operator) | Returnerar sant om samlingen innehåller en given operator. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto)(Operator[], int) | Kopierar operatorer till operatorlistan. |
| [Delete](../../aspose.pdf/operatorcollection/delete#delete_2)(IList&lt;Operator&gt;) | Tar bort operatorer från samlingen. |
| [Delete](../../aspose.pdf/operatorcollection/delete#delete_1)(int) | Tar bort operatör från samlingen. |
| [Delete](../../aspose.pdf/operatorcollection/delete#delete)(Operator[]) | Tar bort operatorer från samlingen. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator)() | Returnerar enumerator för collection |
| [Insert](../../aspose.pdf/operatorcollection/insert#insert_2)(int, IList&lt;Operator&gt;) | Infoga operatorer vid den givna positionen. |
| override [Insert](../../aspose.pdf/operatorcollection/insert#insert)(int, Operator) | Infogar operatorn i samlingen. |
| [Insert](../../aspose.pdf/operatorcollection/insert#insert_1)(int, Operator[]) | Infoga operatorer vid den givna positionen. |
| override [Remove](../../aspose.pdf/operatorcollection/remove)(Operator) | Ta bort operatör från samlingen. |
| [Replace](../../aspose.pdf/operatorcollection/replace)(IList&lt;Operator&gt;) | Ersätt operatorer i samlingen med andra operatorer. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate)() | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate)() | Undertrycker uppdateringsinnehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring)() | Returnerar textrepresentation av operatorn. |

### Se även

* class [BaseOperatorCollection](../baseoperatorcollection)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->