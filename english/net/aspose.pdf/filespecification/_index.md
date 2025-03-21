---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification class. Class representing embedded file
type: docs
weight: 4850
url: /net/aspose.pdf/filespecification/
---
## FileSpecification class

Class representing embedded file.

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Create new empty file specification. |
| [FileSpecification](filespecification/#constructor_3)(string) | Constructor for FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Constructor for file specification. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Constructor for FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Constructor for FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Constructor for FileSpecification. |

## Properties

| Name | Description |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Associated file Relationship. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Gets a collection item of the file specification. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Gets or sets contents file. This property returns data loaded in memory which may cause Out of memory exception for large data. To decrease memory usage please use StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Gets or sets text associated with the file specification. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Gets or sets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Gets encrypted payload. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Gets or sets name of the file system. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | If true, contents of the file will be included in the file specification. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Gets subtype of the embedded file |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Gets or sets file specification name. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Gets file paramteres. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Gets contents of file as stream. Contents is not loaded into memory which allows to decrease memory usage. But this stream does not support positioning and Length property. If you need this features please use Contents property instead. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Gets or sets file specification unicode name. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Dispose contents. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Gets application-specific parameter. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Sets application-specific parameter. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


