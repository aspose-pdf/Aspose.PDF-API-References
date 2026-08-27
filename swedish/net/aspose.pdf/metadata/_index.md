---
title: "Klass Metadata"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Metadata-klass. Tillhandahåller åtkomst till XMP-metadataströmmen"
type: docs
weight: 7090
url: /sv/net/aspose.pdf/metadata/
---
## Metadata class

Tillhandahåller åtkomst till XMP-metadataström.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Hämtar antalet element i samlingen. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Hämtar ordboken med tilläggsfält. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Kontrollerar om samlingen har fast storlek. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Kontrollerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Kontrollerar om samlingen är synkroniserad. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Hämtar eller anger data från metadata. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Hämtar samling av metadata-nycklar. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Hämtar namnrymdshanterare. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Hämtar samlingens synkroniseringsobjekt. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Hämtar värden i metadata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Lägger till ett par med nyckel och värde i ordboken. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Lägger till värde i metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Lägger till pdf‑extension i metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Lägger till värde i metadata. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Rensar metadata. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Kontrollerar om det angivna nyckel‑värde‑paret finns i dictionary. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Kontrollerar om nyckeln finns i metadata. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Fastställer om detta dictionary innehåller den angivna nyckeln. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Returnerar ordboksenumerator. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Returnerar namnrymdens URI efter prefix. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Returnerar prefix efter namnrymdens URI. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registrerar namnrymdens URI. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registrerar namnrymdens URI. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Tar bort nyckel/värde-par från samlingen. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Tar bort post från metadata. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Försöker hitta nyckeln i dictionary och hämtar värdet om den hittas. |

### Se även

* class [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


