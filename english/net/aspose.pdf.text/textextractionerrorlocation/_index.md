---
title: "TextExtractionErrorLocation Class"
linktitle: "TextExtractionErrorLocation"
articleTitle: "TextExtractionErrorLocation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextExtractionErrorLocation class. Represents the location in the PDF document where text extraction error has appeared."
type: docs
weight: 490
url: "/net/aspose.pdf.text/textextractionerrorlocation/"
keywords: "TextExtractionErrorLocation, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextExtractionErrorLocation class

Represents the location in the PDF document where text extraction error has appeared.

```csharp
public sealed class TextExtractionErrorLocation
```

## Properties

| Name | Description |
| --- | --- |
| [FontUsedKey](./fontusedkey/) { get; } | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [FormKey](./formkey/) { get; } | Key (name) of the PDF Form XObject in which contents stream text extraction error has located. Not empty if ObjectType == 'xForm'. |
| [ObjectType](./objecttype/) { get; } | Type of the PDF object (Page or xForm) in which contents stream text extraction error has located. |
| [OperatorIndex](./operatorindex/) { get; } | Index of text showing operator in the contents stream (operator collection) that causes text extraction error. |
| [OperatorString](./operatorstring/) { get; } | Text showing operator that causes text extraction error. |
| [PageNumber](./pagenumber/) { get; } | Number of the document page where text extraction error has located. |
| [Path](./path/) { get; } | Location of the PDF document where text extraction error has appeared. |
| [TextStartPoint](./textstartpoint/) { get; } | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |

## Methods

| Name | Description |
| --- | --- |
| [ToString](./tostring/) | Returns string representation. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

