---
title: "Aspose::Pdf::OperatorSelector class"
linktitle: "OperatorSelector"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OperatorSelector class. Denna klass används för att välja operatorer med Visitor-mallidé i C++."
type: docs
weight: 12200
url: /sv/cpp/aspose.pdf/operatorselector/
---
## OperatorSelector class


Denna klass används för att välja operatörer med Visitor-mallidén.

```cpp
class OperatorSelector : public Aspose::Pdf::IOperatorSelector
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Selected](./get_selected/)() const | Listan över valda objekt. |
| [OperatorSelector](./operatorselector/)() | Initierar en ny instans av klassen [Selector](../). |
| [OperatorSelector](./operatorselector/)(const System::SharedPtr\<Operator\>\&) | Initierar en ny [OperatorSelector](./). |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) override | Besök/välj j-operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) override | Besök/välj EX-operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) override | Besök/välj ET-operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) override | Besök/välj EMC-operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) override | Besök/välj EI operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) override | Besök/välj DP operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) override | Besök/välj Do operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) override | Besök/välj d1 operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) override | Besök/välj d0 operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) override | Besök/välj d operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) override | Besök/välj CS operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) override | Besök/välj cs operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) override | Besök/välj cm operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) override | Besök/välj c operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) override | Besök/välj BX operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) override | Besök/välj BT operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) override | Besök/välj BMC operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) override | Besök/välj BI operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) override | Besök/välj BDC operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) override | Besök/välj B operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) override | Besök/välj b operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) override | Besök/välj B* operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) override | Besök/välj b* operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) override | Besök/välj ' operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) override | Besök/välj '' operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) override | Besök/välj operator f*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) override | Besök/välj f operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) override | Besök/välj F operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) override | Besök/välj g operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) override | Besök/välj G operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) override | Besök/välj gs operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) override | Besök/välj h operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) override | Besök/välj i operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) override | Besök/välj ID operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) override | Besök/välj J operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) override | Besök/välj k operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) override | Besök/välj K operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) override | Besök/välj l operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) override | Besök/välj m operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) override | Besök/välj M operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) override | Besök/välj MP operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) override | Besök/välj n operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) override | Besök/välj q operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) override | Besök/välj Q operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) override | Besök/välj re operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) override | Besök/välj rg operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) override | Besök/välj RG operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) override | Besök/välj ri operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) override | Besök/välj s operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) override | Besök/välj S operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) override | Besök/välj sc operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) override | Besök/välj SC operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) override | Besök/välj scn operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) override | Besök/välj SCN operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) override | Besök/välj sh operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) override | Besök/välj T* operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) override | Besök/välj Tc operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) override | Besök/välj Td operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) override | Besök/välj TD operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) override | Besök/välj Tf operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) override | Besök/välj Tj operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) override | Besök/välj TJ operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) override | Besök/välj TL operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) override | Besök/välj Tm operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) override | Besök/välj Tr operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) override | Besök/välj Ts operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) override | Besök/välj Tw operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) override | Besök/välj Tz operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) override | Besök/välj v operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) override | Besök/välj W* operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) override | Besök/välj w operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) override | Besök/välj W operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) override | Besök/välj y operator. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) override | Besök/välj any text operator operator. |
## Se även

* Class [IOperatorSelector](../ioperatorselector/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
