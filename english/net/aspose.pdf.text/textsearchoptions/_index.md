---
title: "TextSearchOptions Class"
linktitle: "TextSearchOptions"
articleTitle: "TextSearchOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextSearchOptions class. Represents text search options"
type: docs
weight: 660
url: "/net/aspose.pdf.text/textsearchoptions/"
keywords: "TextSearchOptions, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextSearchOptions class

Represents text search options

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSearchOptions](./textsearchoptions/#constructor)(*bool*) | Initializes new instance of the [`TextSearchOptions`](../../aspose.pdf.text/textsearchoptions/) object. |
| [TextSearchOptions](./textsearchoptions/#constructor_1)(*[Rectangle](../../aspose.pdf.drawing/rectangle/)*) | Initializes new instance of the [`TextSearchOptions`](../../aspose.pdf.text/textsearchoptions/) object. |
| [TextSearchOptions](./textsearchoptions/#constructor_2)(*[Rectangle](../../aspose.pdf.drawing/rectangle/), bool*) | Initializes new instance of the [`TextSearchOptions`](../../aspose.pdf.text/textsearchoptions/) object. |

## Properties

| Name | Description |
| --- | --- |
| [IgnoreResourceFontErrors](./ignoreresourcefonterrors/) { get; set; } | Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. |
| [IgnoreShadowText](./ignoreshadowtext/) { get; set; } | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. |
| [IsRegularExpressionUsed](./isregularexpressionused/) { get; set; } | Gets or sets indication that regular expression is used. |
| [LimitToPageBounds](./limittopagebounds/) { get; set; } | Gets or sets indication that text is searched within the page bounds. |
| [LogTextExtractionErrors](./logtextextractionerrors/) { get; set; } | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. |
| [Rectangle](./rectangle/) { get; set; } | Gets or sets rectangle that bounds the searched text. |
| [SearchForTextRelatedGraphics](./searchfortextrelatedgraphics/) { get; set; } | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. |
| [SearchInAnnotations](./searchinannotations/) { get; set; } | Gets or sets value that permits searching for text in Annotations. |
| [StoredGraphicElementsMaxCount](./storedgraphicelementsmaxcount/) { get; set; } | Gets or sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. |
| [UseFontEngineEncoding](./usefontengineencoding/) { get; set; } | Gets or sets indication that text will be searched using font engine encoding. |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

