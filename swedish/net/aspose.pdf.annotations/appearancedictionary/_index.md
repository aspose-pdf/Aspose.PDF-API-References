---
title: "Klassen AppearanceDictionary"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.AppearanceDictionary-klass. Annotationsutseendedictionary som specificerar hur annotationen ska visas visuellt på sidan."
type: docs
weight: 1580
url: /sv/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

Ordbok för annoteringsutseende som specificerar hur annotationen ska visas visuellt på sidan.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Hämtar antalet element som finns i ordboken. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Hämtar ett värde som indikerar om ordboken har en fast storlek. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Hämtar ett värde som indikerar om ordboken är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till ordboken är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Representerar ett bekvämt sätt att hämta utseendeströmmar. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Hämtar nycklarna i ordboken. Om utseendeordboken har underordböcker, så innehåller [`Keys`](./keys/) (N&#x7C;R&#x7C;D).state‑värden, där N – normal utseende, R – rullningsutseende, D – nedtryckt utseende och state – namnet på tillståndet (t.ex. På, Av för kryssrutor). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till ordboken. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Hämtar listan med ordbokens värden. Resultatsamlingen innehåller listan med XForm‑objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Lägger till ett par med nyckel och värde i ordboken. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Lägg till X‑form för angiven nyckel. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Tar bort alla element från ordboken. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Kontrollerar om det angivna nyckel‑värde‑paret finns i dictionary. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Fastställer om detta dictionary innehåller den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Kopierar elementen i ordboken till en array, med start vid ett specifikt array‑index. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Returnerar ett IDictionaryEnumerator‑objekt för ordboken. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Tar bort nyckel/värde‑par från samlingen. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Tar bort nyckeln från dictionary. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Försöker hitta nyckeln i dictionary och hämtar värdet om den hittas. |

### Se även

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


