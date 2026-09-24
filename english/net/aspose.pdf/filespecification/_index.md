---
title: "FileSpecification Class"
linktitle: "FileSpecification"
articleTitle: "FileSpecification"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.FileSpecification class. Class representing embedded file."
type: docs
weight: 910
url: "/net/aspose.pdf/filespecification/"
keywords: "FileSpecification, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FileSpecification class

Class representing embedded file.

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [FileSpecification](./filespecification/#constructor) | Create new empty file specification. |
| [FileSpecification](./filespecification/#constructor_1)(*string*) | Constructor for FileSpecification. |
| [FileSpecification](./filespecification/#constructor_2)(*Stream, string*) | Constructor for file specification. |
| [FileSpecification](./filespecification/#constructor_3)(*string, string*) | Constructor for FileSpecification. |
| [FileSpecification](./filespecification/#constructor_4)(*string, [Annotation](../../aspose.pdf.annotations/annotation/)*) | Constructor for FileSpecification. |
| [FileSpecification](./filespecification/#constructor_5)(*Stream, string, string*) | Constructor for FileSpecification. |

## Properties

| Name | Description |
| --- | --- |
| [AFRelationship](./afrelationship/) { get; set; } | Associated file Relationship. |
| [CollectionItem](./collectionitem/) { get; } | Gets a collection item of the file specification. |
| [Contents](./contents/) { get; set; } | Gets or sets contents file. |
| [Description](./description/) { get; set; } | Gets or sets text associated with the file specification. |
| [Encoding](./encoding/) { get; set; } | Gets or sets encoding format. |
| [EncryptedPayload](./encryptedpayload/) { get; } | Gets encrypted payload. |
| [FileSystem](./filesystem/) { get; set; } | Gets or sets name of the file system. |
| [IncludeContents](./includecontents/) { get; set; } | If true, contents of the file will be included in the file specification. |
| [MIMEType](./mimetype/) { get; set; } | Gets subtype of the embedded file. |
| [Name](./name/) { get; set; } | Gets or sets file specification name. |
| [Params](./params/) { get; set; } | Gets file paramteres. |
| [StreamContents](./streamcontents/) { get; } | Gets contents of file as stream. |
| [UnicodeName](./unicodename/) { get; set; } | Gets or sets file specification unicode name. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](./dispose/) | Dispose contents. |
| [GetFileName](./getfilename/)(*string, bool*) | Gets the file name using the available file specification names, the specified fallback name,. |
| [GetValue](./getvalue/)(*string*) | Gets application-specific parameter. |
| [SetValue](./setvalue/)(*string, string*) | Sets application-specific parameter. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

