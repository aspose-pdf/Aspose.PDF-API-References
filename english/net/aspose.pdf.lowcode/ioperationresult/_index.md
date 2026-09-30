---
title: "IOperationResult Interface"
linktitle: "IOperationResult"
articleTitle: "IOperationResult"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.IOperationResult interface. General operation result interface that defines common methods that concrete plugin operation result should im..."
type: docs
weight: 420
url: "/net/aspose.pdf.lowcode/ioperationresult/"
product_version: "26.9.0"
---
## IOperationResult interface

General operation result interface that defines common methods that concrete plugin operation result should implement.

```csharp
public interface IOperationResult
```

## Properties

| Name | Description |
| --- | --- |
| [Data](./data/) { get; } | Gets raw data. |
| [IsFile](./isfile/) { get; } | Indicates whether the result is a path to an output file. |
| [IsStream](./isstream/) { get; } | Indicates whether the result is an output stream. |
| [IsString](./isstring/) { get; } | Indicates whether the result is a text string. |

## Methods

| Name | Description |
| --- | --- |
| [ToFile](./tofile/)() | Tries to convert the result to the file. |
| [ToStream](./tostream/)() | Tries to convert the result to the stream object. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

