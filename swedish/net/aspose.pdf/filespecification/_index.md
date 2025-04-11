---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification klass. Klass som representerar inbäddad fil
type: docs
weight: 4850
url: /sv/net/aspose.pdf/filespecification/
---
## FileSpecification klass

Klass som representerar inbäddad fil.

```csharp
public sealed class FileSpecification : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Skapa ny tom filspecifikation. |
| [FileSpecification](filespecification/#constructor_3)(string) | Konstruktör för FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Konstruktör för filspecifikation. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Konstruktör för FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Konstruktör för FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Konstruktör för FileSpecification. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Associerad filrelation. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Hämtar ett samlingsobjekt av filspecifikationen. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Hämtar eller ställer in innehållsfil. Denna egenskap returnerar data som laddas i minnet vilket kan orsaka Out of memory-undantag för stora data. För att minska minnesanvändningen, vänligen använd StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Hämtar eller ställer in text kopplad till filspecifikationen. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Hämtar eller ställer in kodningsformat. Möjliga värden: Zip - filen är komprimerad med ZIP, None - filen är inte komprimerad. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Hämtar krypterad nyttolast. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Hämtar eller ställer in namnet på filsystemet. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Om sant, kommer innehållet i filen att inkluderas i filspecifikationen. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Hämtar underkategori av den inbäddade filen |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Hämtar eller ställer in filspecifikationens namn. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Hämtar filparametrar. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Hämtar innehållet i filen som ström. Innehållet laddas inte in i minnet vilket gör att minnesanvändningen kan minskas. Men denna ström stöder inte positionering och Length-egenskapen. Om du behöver dessa funktioner, vänligen använd Contents-egenskapen istället. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Hämtar eller ställer in filspecifikationens unicode-namn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Avyttra innehåll. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Hämtar applikationsspecifik parameter. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Ställer in applikationsspecifik parameter. |

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)