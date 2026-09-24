---
title: "ComHelper Class"
linktitle: "ComHelper"
articleTitle: "ComHelper"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.ComHelper class. Provides methods for COM clients to load a document into Aspose.Pdf."
type: docs
weight: 420
url: "/net/aspose.pdf/comhelper/"
keywords: "ComHelper, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ComHelper class

Provides methods for COM clients to load a document into Aspose.Pdf.

```csharp
public class ComHelper
```

## Constructors

| Name | Description |
| --- | --- |
| [ComHelper](./comhelper/#constructor) | Initializes a new instance of the ComHelper class. |

## Methods

| Name | Description |
| --- | --- |
| [OpenFile](./openfile/)(*string*) | Just create and return Document using . The same as `#ctor`. |
| [OpenFile](./openfile/)(*string, string*) | Initialize and return new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [OpenFile](./openfile/)(*string, LoadOptions*) | Open an existing document from a file providing necessary converting oprions to get pdf document. |
| [OpenFile](./openfile/)(*string, string, bool*) | Initialize new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [OpenStream](./openstream/)(*Stream*) | Initialize and return new Document instance from the stream. |
| [OpenStream](./openstream/)(*Stream, string*) | Initialize and return new Document instance from the stream. |
| [OpenStream](./openstream/)(*Stream, bool*) | Initialize and return new Document instance from the stream. |
| [OpenStream](./openstream/)(*Stream, LoadOptions*) | Open and return an existing document from a stream providing necessary converting to get pdf document. |
| [OpenStream](./openstream/)(*Stream, string, bool*) | Initialize and return new Document instance from the stream. |

## Remarks

Use the ComHelper class to load a document from a file or stream into a Document object in a COM application.
 The Document class provides a default constructor to create a new document
 and also provides overloaded constructors to load a document from a file or stream.
 If you are using Aspose.Words from a .NET application, you can use all of the Document constructors directly, but if you are using Aspose.Pdf from a COM application,
 only the default Document constructor is available.

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

