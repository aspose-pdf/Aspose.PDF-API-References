---
title: "SetGlyphsPositionShowText Class"
linktitle: "SetGlyphsPositionShowText"
articleTitle: "SetGlyphsPositionShowText"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.SetGlyphsPositionShowText class. Class representing TJ operator (show text with glyph positioning)."
type: docs
weight: 630
url: "/net/aspose.pdf.operators/setglyphspositionshowtext/"
keywords: "SetGlyphsPositionShowText, Aspose.Pdf.Operators, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SetGlyphsPositionShowText class

Class representing TJ operator (show text with glyph positioning).

```csharp
public class SetGlyphsPositionShowText : TextShowOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetGlyphsPositionShowText](./setglyphspositionshowtext/)(IEnumerable<GlyphPosition>) | Constructor for TJ operator. |

## Properties

| Name | Description |
| --- | --- |
| [GlyphPositions](./glyphpositions/) { get; } | Returns positions of glyphs. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| override [Text](./text/) { get; } | Gets text from operator argument (glyph positioning is ignored). |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| override [ToString](./tostring/)() | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also

* class [TextShowOperator](../textshowoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)

