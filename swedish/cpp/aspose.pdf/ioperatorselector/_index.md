---
title: "Aspose::Pdf::IOperatorSelector class"
linktitle: "IOperatorSelector"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::IOperatorSelector class. Definierar Visitor för att besöka olika pdf-operatorer i C++."
type: docs
weight: 8900
url: /sv/cpp/aspose.pdf/ioperatorselector/
---
## IOperatorSelector class


Definierar Visitor för att besöka olika pdf-operatorer.

```cpp
class IOperatorSelector : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) | Besök/välj f operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) | Besök/välj F operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) | Besök/välj operator f*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) | Besök/välj G operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) | Besök/välj g operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) | Besök/välj gs operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) | Besök/välj h operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) | Besök/välj i operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) | Besök/välj ID operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) | Besök/välj ri operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) | Besök/välj J operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) | Besök/välj M operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) | Besök/välj MP operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) | Besök/välj n operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) | Besök/välj q operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) | Besök/välj Q operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) | Besök/välj re operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) | Besök/välj RG operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) | Besök/välj rg operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) | Besök/välj K operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) | Besök/välj k operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) | Besök/välj l operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) | Besök/välj m operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) | Besök/välj Tw operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) | Besök/välj s operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) | Besök/välj TD operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) | Besök/välj Tf operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) | Besök/välj Tj operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) | Besök/välj TJ operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) | Besök/välj TL operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) | Besök/välj Tm operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) | Besök/välj Tr operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) | Besök/välj Ts operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) | Besök/välj S operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) | Besök/välj SC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) | Besök/välj sc operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) | Besök/välj SCN operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) | Besök/välj scn operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) | Besök/välj sh operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) | Besök/välj T* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) | Besök/välj Tc operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) | Besök/välj Td operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) | Besök/välj y operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) | Besök/välj W* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) | Besök/välj Tz operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) | Besök/välj v operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) | Besök/välj W operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) | Besök/välj w operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) | Besök/välj j-operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) | Besök/välj EX-operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) | Besök/välj ET-operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) | Besök/välj EMC-operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) | Besök/välj EI operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) | Besök/välj DP operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) | Besök/välj Do operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) | Besök/välj d operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) | Besök/välj d0 operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) | Besök/välj d1 operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) | Besök/välj CS operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) | Besök/välj cs operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) | Besök/välj cm operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) | Besök/välj c operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) | Besök/välj BX operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) | Besök/välj BT operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) | Besök/välj BMC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) | Besök/välj BI operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) | Besök/välj BDC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) | Besök/välj B operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) | Besök/välj b operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) | Besök/välj B* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) | Besök/välj b* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) | Besök/välj ' operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) | Besök/välj '' operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) | Besök/välj any text operator operator. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
