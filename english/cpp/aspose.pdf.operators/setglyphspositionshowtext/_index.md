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
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepts visitor object to process operator. |
| [get_GlyphPositions](./get_glyphpositions/)() const | Returns positions of glyphs. |
| [get_Text](./get_text/)() override | Gets text from operator argument (glyph positioning is ignored). |
| [SetGlyphsPositionShowText](./setglyphspositionshowtext/)(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GlyphPosition\>\>\>) | Constructor for TJ operator. |
| [ToString](./tostring/)() const override | Returns text representation of operator. |
## See Also

* Class [TextShowOperator](../textshowoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
