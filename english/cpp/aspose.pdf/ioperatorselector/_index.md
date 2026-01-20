---
title: Aspose::Pdf::IOperatorSelector class
linktitle: IOperatorSelector
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::IOperatorSelector class. Defines Visitor for visiting different pdf operators in C++.'
type: docs
weight: 8900
url: /cpp/aspose.pdf/ioperatorselector/
---
## IOperatorSelector class


Defines Visitor for visiting different pdf operators.

```cpp
class IOperatorSelector : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) | Visit/select f operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) | Visit/select F operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) | Visit/select operator f*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) | Visit/select G operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) | Visit/select g operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) | Visit/select gs operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) | Visit/select h operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) | Visit/select i operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) | Visit/select ID operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) | Visit/select ri operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) | Visit/select J operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) | Visit/select M operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) | Visit/select MP operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) | Visit/select n operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) | Visit/select q operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) | Visit/select Q operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) | Visit/select re operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) | Visit/select RG operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) | Visit/select rg operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) | Visit/select K operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) | Visit/select k operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) | Visit/select l operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) | Visit/select m operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) | Visit/select Tw operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) | Visit/select s operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) | Visit/select TD operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) | Visit/select Tf operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) | Visit/select Tj operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) | Visit/select TJ operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) | Visit/select TL operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) | Visit/select Tm operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) | Visit/select Tr operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) | Visit/select Ts operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) | Visit/select S operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) | Visit/select SC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) | Visit/select sc operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) | Visit/select SCN operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) | Visit/select scn operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) | Visit/select sh operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) | Visit/select T* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) | Visit/select Tc operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) | Visit/select Td operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) | Visit/select y operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) | Visit/select W* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) | Visit/select Tz operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) | Visit/select v operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) | Visit/select W operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) | Visit/select w operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) | Visit/select j operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) | Visit/select EX operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) | Visit/select ET operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) | Visit/select EMC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) | Visit/select EI operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) | Visit/select DP operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) | Visit/select Do operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) | Visit/select d operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) | Visit/select d0 operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) | Visit/select d1 operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) | Visit/select CS operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) | Visit/select cs operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) | Visit/select cm operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) | Visit/select c operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) | Visit/select BX operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) | Visit/select BT operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) | Visit/select BMC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) | Visit/select BI operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) | Visit/select BDC operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) | Visit/select B operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) | Visit/select b operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) | Visit/select B* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) | Visit/select b* operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) | Visit/select ' operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) | Visit/select '' operator. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) | Visit/select any text operator operator. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
