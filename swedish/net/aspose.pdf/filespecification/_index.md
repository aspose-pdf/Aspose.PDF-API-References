---
title: "Klass FileSpecification"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.FileSpecification-klass. Klass som representerar en inbäddad fil"
type: docs
weight: 4970
url: /sv/net/aspose.pdf/filespecification/
---
## FileSpecification class

Klass som representerar inbäddad fil.

```csharp
public sealed class FileSpecification : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Skapa en ny tom filspecificering. |
| [FileSpecification](filespecification/#constructor_3)(string) | Konstruktor för FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Konstruktor för filspecificering. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Konstruktor för FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Konstruktor för FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Konstruktor för FileSpecification. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Associerad filrelation. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Hämtar ett samlingsobjekt från filspecificeringen. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Hämtar eller anger innehållsfil. Denna egenskap returnerar data som laddas i minnet, vilket kan orsaka Out of memory exception för stora data. För att minska minnesanvändningen, använd StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Hämtar eller anger text som är associerad med filspecificeringen. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Hämtar eller anger kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Hämtar krypterad nyttolast. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Hämtar eller anger namn på filsystemet. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Om true, kommer filens innehåll att inkluderas i filspecificeringen. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Hämtar undertyp för den inbäddade filen |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Hämtar eller anger namn på filspecificering. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Hämtar filparametrar. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Hämtar filens innehåll som en ström. Innehållet laddas inte in i minnet, vilket möjliggör minskad minnesanvändning. Men denna ström stöder inte positionering och Length-egenskapen. Om du behöver dessa funktioner, använd egenskapen Contents istället. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Hämtar eller anger unicode-namn för filspecificering. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Rensa innehållet. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Hämtar programspecifik parameter. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Ställer in programspecifik parameter. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


