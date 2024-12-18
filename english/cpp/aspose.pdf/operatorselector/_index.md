---
title: Aspose::Pdf::OperatorSelector class
linktitle: OperatorSelector
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorSelector class. This class is used for selecting operators using Visitor template idea in C++.'
type: docs
weight: 11800
url: /cpp/aspose.pdf/operatorselector/
---
## OperatorSelector class


This class is used for selecting operators using Visitor template idea.

```cpp
class OperatorSelector : public Aspose::Pdf::IOperatorSelector
```

## Methods

| Method | Description |
| --- | --- |
| [get_Selected](./get_selected/)() const | The list of selected objects. |
| [OperatorSelector](./operatorselector/)() | Initializes new instance of the [Selector](../) class. |
| [OperatorSelector](./operatorselector/)(System::SharedPtr\<Operator\>) | Initializes new [OperatorSelector](./). |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetLineJoin\>) override | Visit/select j operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EX\>) override | Visit/select EX operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ET\>) override | Visit/select ET operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EMC\>) override | Visit/select EMC operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EI\>) override | Visit/select EI operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::DP\>) override | Visit/select DP operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::Do\>) override | Visit/select Do operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetCharWidthBoundingBox\>) override | Visit/select d1 operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetCharWidth\>) override | Visit/select d0 operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetDash\>) override | Visit/select d operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetColorSpaceStroke\>) override | Visit/select CS operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetColorSpace\>) override | Visit/select cs operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ConcatenateMatrix\>) override | Visit/select cm operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::CurveTo\>) override | Visit/select c operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::BX\>) override | Visit/select BX operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::BT\>) override | Visit/select BT operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::BMC\>) override | Visit/select BMC operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::BI\>) override | Visit/select BI operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::BDC\>) override | Visit/select BDC operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::FillStroke\>) override | Visit/select B operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ClosePathFillStroke\>) override | Visit/select b operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EOFillStroke\>) override | Visit/select B* operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ClosePathEOFillStroke\>) override | Visit/select b* operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::MoveToNextLineShowText\>) override | Visit/select ' operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>) override | Visit/select '' operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EOFill\>) override | Visit/select operator f*. |
| [Visit](./visit/)(System::SharedPtr\<Operators::Fill\>) override | Visit/select f operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ObsoleteFill\>) override | Visit/select F operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetGray\>) override | Visit/select g operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetGrayStroke\>) override | Visit/select G operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::GS\>) override | Visit/select gs operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ClosePath\>) override | Visit/select h operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetFlat\>) override | Visit/select i operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ID\>) override | Visit/select ID operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetLineCap\>) override | Visit/select J operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetCMYKColor\>) override | Visit/select k operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetCMYKColorStroke\>) override | Visit/select K operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::LineTo\>) override | Visit/select l operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::MoveTo\>) override | Visit/select m operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetMiterLimit\>) override | Visit/select M operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::MP\>) override | Visit/select MP operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EndPath\>) override | Visit/select n operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::GSave\>) override | Visit/select q operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::GRestore\>) override | Visit/select Q operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::Re\>) override | Visit/select re operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetRGBColor\>) override | Visit/select rg operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetRGBColorStroke\>) override | Visit/select RG operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetColorRenderingIntent\>) override | Visit/select ri operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ClosePathStroke\>) override | Visit/select s operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::Stroke\>) override | Visit/select S operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetColor\>) override | Visit/select sc operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetColorStroke\>) override | Visit/select SC operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetAdvancedColor\>) override | Visit/select scn operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetAdvancedColorStroke\>) override | Visit/select SCN operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ShFill\>) override | Visit/select sh operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::MoveToNextLine\>) override | Visit/select T* operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetCharacterSpacing\>) override | Visit/select Tc operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::MoveTextPosition\>) override | Visit/select Td operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::MoveTextPositionSetLeading\>) override | Visit/select TD operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SelectFont\>) override | Visit/select Tf operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::ShowText\>) override | Visit/select Tj operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetGlyphsPositionShowText\>) override | Visit/select TJ operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetTextLeading\>) override | Visit/select TL operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetTextMatrix\>) override | Visit/select Tm operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetTextRenderingMode\>) override | Visit/select Tr operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetTextRise\>) override | Visit/select Ts operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetWordSpacing\>) override | Visit/select Tw operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetHorizontalTextScaling\>) override | Visit/select Tz operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::CurveTo1\>) override | Visit/select v operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::EOClip\>) override | Visit/select W* operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::SetLineWidth\>) override | Visit/select w operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::Clip\>) override | Visit/select W operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::CurveTo2\>) override | Visit/select y operator. |
| [Visit](./visit/)(System::SharedPtr\<Operators::TextOperator\>) override | Visit/select any text operator operator. |
## See Also

* Class [IOperatorSelector](../ioperatorselector/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
