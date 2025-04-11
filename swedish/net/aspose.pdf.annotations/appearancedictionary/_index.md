---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary klass. Anteckningens utseendediktionär som specificerar hur anteckningen ska presenteras visuellt på sidan
type: docs
weight: 1490
url: /sv/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary klass

Anteckningens utseendediktionär som specificerar hur anteckningen ska presenteras visuellt på sidan.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Hämtar antalet element som finns i diktionen. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Hämtar ett värde som indikerar om diktionen har en fast storlek. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Hämtar ett värde som indikerar om diktionen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till diktionen är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Representerar en bekväm form för att hämta utseendeströmmar. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Hämtar nycklarna i diktionen. Om utseendediktionen har underdiktioner, då innehåller [`Keys`](./keys/) (N&#x7C;R&#x7C;D).state värden, där N - normalt utseende, R - rullande utseende, D - nedtryckt utseende och state - namnet på tillståndet (t.ex. På, Av för kryssrutor). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till diktionen. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Hämtar listan över diktionens värden. Resultatsamlingen innehåller listan över XForm-objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Lägger till ett par med nyckel och värde i diktionen. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Lägger till X-form för angiven nyckel. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Tar bort alla element från diktionen. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Kontrollerar om det angivna nyckel-värde-paret finns i diktionen. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Bestämmer om denna diktion innehåller den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Kopierar elementen i diktionen till en Array, med början vid ett särskilt Array-index. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Returnerar ett IDictionaryEnumerator-objekt för diktionen. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Tar bort nyckel/värde-paret från samlingen. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Tar bort nyckeln från diktionen. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Försöker att hitta nyckeln i diktionen och hämtar värdet om det hittas. |

### Se Även

* klass [XForm](../../aspose.pdf/xform/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* sammansättning [Aspose.PDF](../../)