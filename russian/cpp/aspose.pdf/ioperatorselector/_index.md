---
title: "Класс Aspose::Pdf::IOperatorSelector"
linktitle: "IOperatorSelector"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::IOperatorSelector. Определяет Visitor для посещения различных pdf‑операторов в C++."
type: docs
weight: 8900
url: /ru/cpp/aspose.pdf/ioperatorselector/
---
## IOperatorSelector class


Определяет Visitor для обхода различных pdf‑операторов.

```cpp
class IOperatorSelector : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) | Посетить/выбрать оператор f. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) | Посетить/выбрать оператор F. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) | Посетить/выбрать оператор f*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) | Посетить/выбрать оператор G. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) | Посетить/выбрать оператор g. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) | Посетить/выбрать оператор gs. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) | Посетить/выбрать оператор h. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) | Посетить/выбрать оператор i. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) | Посетить/выбрать оператор ID. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) | Посетить/выбрать ri оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) | Посетить/выбрать оператор J. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) | Посетить/выбрать оператор M. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) | Посетить/выбрать оператор MP. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) | Посетить/выбрать оператор n. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) | Посетить/выбрать q оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) | Посетить/выбрать Q оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) | Посетить/выбрать re оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) | Посетить/выбрать RG оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) | Посетить/выбрать rg оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) | Посетить/выбрать оператор K. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) | Посетить/выбрать оператор k. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) | Посетить/выбрать оператор l. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) | Посетить/выбрать оператор m. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) | Посетить/выбрать Tw оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) | Посетить/выбрать s оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) | Посетить/выбрать TD оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) | Посетить/выбрать Tf оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) | Посетить/выбрать Tj оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) | Посетить/выбрать TJ оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) | Посетить/выбрать TL оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) | Посетить/выбрать Tm оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) | Посетить/выбрать Tr оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) | Посетить/выбрать Ts оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) | Посетить/выбрать S оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) | Посетить/выбрать SC оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) | Посетить/выбрать sc оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) | Посетить/выбрать SCN оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) | Посетить/выбрать scn оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) | Посетить/выбрать sh оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) | Посетить/выбрать T* оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) | Посетить/выбрать Tc оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) | Посетить/выбрать Td оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) | Посетить/выбрать оператор y. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) | Посетить/выбрать оператор W*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) | Посетить/выбрать оператор Tz. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) | Посетить/выбрать оператор v. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) | Посетить/выбрать оператор W. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) | Посетить/выбрать оператор w. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) | Visit/select j оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) | Visit/select EX оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) | Visit/select ET оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) | Visit/select EMC оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) | Visit/select EI оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) | Visit/select DP оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) | Visit/select Do оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) | Visit/select d оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) | Visit/select d0 оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) | Visit/select d1 оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) | Visit/select CS оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) | Visit/select cs оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) | Visit/select cm оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) | Visit/select c оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) | Visit/select BX оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) | Visit/select BT оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) | Visit/select BMC оператор. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) | Посетить/выбрать оператор BI. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) | Посетить/выбрать оператор BDC. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) | Посетить/выбрать оператор B. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) | Посетить/выбрать оператор b. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) | Посетить/выбрать оператор B*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) | Посетить/выбрать оператор b*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) | Посетить/выбрать оператор '. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) | Посетить/выбрать оператор ''. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) | Посетить/выбрать любой текстовый оператор оператор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
