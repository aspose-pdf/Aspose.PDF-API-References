---
title: "Aspose::Pdf::OperatorSelector класс"
linktitle: "OperatorSelector"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::OperatorSelector класс. Этот класс используется для выбора операторов с использованием идеи шаблона Visitor в C++."
type: docs
weight: 12200
url: /ru/cpp/aspose.pdf/operatorselector/
---
## OperatorSelector class


Этот класс используется для выбора операторов с использованием идеи шаблона Visitor.

```cpp
class OperatorSelector : public Aspose::Pdf::IOperatorSelector
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Selected](./get_selected/)() const | Список выбранных объектов. |
| [OperatorSelector](./operatorselector/)() | Инициализирует новый экземпляр класса [Selector](../). |
| [OperatorSelector](./operatorselector/)(const System::SharedPtr\<Operator\>\&) | Инициализирует новый [OperatorSelector](./). |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) override | Visit/select j оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) override | Visit/select EX оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) override | Visit/select ET оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) override | Visit/select EMC оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) override | Visit/select EI оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) override | Visit/select DP оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) override | Visit/select Do оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) override | Visit/select d1 оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) override | Visit/select d0 оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) override | Visit/select d оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) override | Visit/select CS оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) override | Visit/select cs оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) override | Visit/select cm оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) override | Visit/select c оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) override | Visit/select BX оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) override | Visit/select BT оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) override | Visit/select BMC оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) override | Посетить/выбрать оператор BI. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) override | Посетить/выбрать оператор BDC. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) override | Посетить/выбрать оператор B. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) override | Посетить/выбрать оператор b. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) override | Посетить/выбрать оператор B*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) override | Посетить/выбрать оператор b*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) override | Посетить/выбрать оператор '. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) override | Посетить/выбрать оператор ''. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) override | Посетить/выбрать оператор f*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) override | Посетить/выбрать оператор f. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) override | Посетить/выбрать оператор F. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) override | Посетить/выбрать оператор g. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) override | Посетить/выбрать оператор G. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) override | Посетить/выбрать оператор gs. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) override | Посетить/выбрать оператор h. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) override | Посетить/выбрать оператор i. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) override | Посетить/выбрать оператор ID. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) override | Посетить/выбрать оператор J. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) override | Посетить/выбрать оператор k. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) override | Посетить/выбрать оператор K. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) override | Посетить/выбрать оператор l. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) override | Посетить/выбрать оператор m. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) override | Посетить/выбрать оператор M. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) override | Посетить/выбрать оператор MP. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) override | Посетить/выбрать оператор n. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) override | Посетить/выбрать q оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) override | Посетить/выбрать Q оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) override | Посетить/выбрать re оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) override | Посетить/выбрать rg оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) override | Посетить/выбрать RG оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) override | Посетить/выбрать ri оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) override | Посетить/выбрать s оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) override | Посетить/выбрать S оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) override | Посетить/выбрать sc оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) override | Посетить/выбрать SC оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) override | Посетить/выбрать scn оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) override | Посетить/выбрать SCN оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) override | Посетить/выбрать sh оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) override | Посетить/выбрать T* оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) override | Посетить/выбрать Tc оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) override | Посетить/выбрать Td оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) override | Посетить/выбрать TD оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) override | Посетить/выбрать Tf оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) override | Посетить/выбрать Tj оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) override | Посетить/выбрать TJ оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) override | Посетить/выбрать TL оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) override | Посетить/выбрать Tm оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) override | Посетить/выбрать Tr оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) override | Посетить/выбрать Ts оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) override | Посетить/выбрать Tw оператор. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) override | Посетить/выбрать оператор Tz. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) override | Посетить/выбрать оператор v. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) override | Посетить/выбрать оператор W*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) override | Посетить/выбрать оператор w. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) override | Посетить/выбрать оператор W. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) override | Посетить/выбрать оператор y. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) override | Посетить/выбрать любой текстовый оператор оператор. |
## См. также

* Class [IOperatorSelector](../ioperatorselector/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
