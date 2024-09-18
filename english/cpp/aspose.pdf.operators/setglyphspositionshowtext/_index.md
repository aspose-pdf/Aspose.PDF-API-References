---
title: Aspose::Pdf::Operators::SetGlyphsPositionShowText class
linktitle: SetGlyphsPositionShowText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::SetGlyphsPositionShowText class. Class representing TJ operator (show text with glyph positioning) in C++.'
type: docs
weight: 6000
url: /cpp/aspose.pdf.operators/setglyphspositionshowtext/
---
## SetGlyphsPositionShowText class


Class representing TJ operator (show text with glyph positioning).

```cpp
class SetGlyphsPositionShowText : public Aspose::Pdf::Operators::TextShowOperator
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) override | Accepts visitor object to process operator. |
| [get_GlyphPositions](./get_glyphpositions/)() const | Returns positions of glyphs. |
| [get_Index](../../aspose.pdf/operator/get_index/)() | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| [get_Text](./get_text/)() override | Gets text from operator argument (glyph positioning is ignored). |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(System::SharedPtr\<Operator\>) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [set_Index](../../aspose.pdf/operator/set_index/)(int32_t) | [Operator](../../aspose.pdf/operator/) index in page operators list. |
| virtual [set_Text](../textshowoperator/set_text/)(System::String) | Gets text which operator out on the page. |
| [SetGlyphsPositionShowText](./setglyphspositionshowtext/)(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GlyphPosition\>\>\>) | Constructor for TJ operator. |
| [TextOperator](../textoperator/textoperator/)() | Initializes operator. |
| [TextOperator](../textoperator/textoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | [Text](../../aspose.pdf.text/) operator which accepts text properties. |
| [TextShowOperator](../textshowoperator/textshowoperator/)() | Initializes [TextShowOperator](../textshowoperator/). |
| [TextShowOperator](../textshowoperator/textshowoperator/)(System::SharedPtr\<Aspose::Pdf::Facades::TextProperties\>) | Initializes [TextShowOperator](../textshowoperator/) which allows to pass TextProperties. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(System::SharedPtr\<Operator\>) | Compares this instance with the given object. |
## See Also

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
