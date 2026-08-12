---
title: "Aspose::Pdf::OperatorSelector clase"
linktitle: "OperatorSelector"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::OperatorSelector clase. Esta clase se usa para seleccionar operadores usando la idea de plantilla Visitor en C++."
type: docs
weight: 12200
url: /es/cpp/aspose.pdf/operatorselector/
---
## OperatorSelector class


Esta clase se usa para seleccionar operadores utilizando la idea de plantilla Visitor.

```cpp
class OperatorSelector : public Aspose::Pdf::IOperatorSelector
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Selected](./get_selected/)() const | La lista de objetos seleccionados. |
| [OperatorSelector](./operatorselector/)() | Inicializa una nueva instancia de la clase [Selector](../). |
| [OperatorSelector](./operatorselector/)(const System::SharedPtr\<Operator\>\&) | Inicializa un nuevo [OperatorSelector](./). |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) override | Visitar/seleccionar operador j. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) override | Visitar/seleccionar operador EX. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) override | Visitar/seleccionar operador ET. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) override | Visitar/seleccionar operador EMC. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) override | Visitar/seleccionar operador EI. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) override | Visitar/seleccionar operador DP. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) override | Visitar/seleccionar operador Do. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) override | Visitar/seleccionar operador d1. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) override | Visitar/seleccionar operador d0. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) override | Visitar/seleccionar operador d. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) override | Visitar/seleccionar operador CS. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) override | Visitar/seleccionar operador cs. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) override | Visitar/seleccionar operador cm. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) override | Visitar/seleccionar operador c. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) override | Visitar/seleccionar operador BX. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) override | Visitar/seleccionar operador BT. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) override | Visitar/seleccionar operador BMC. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) override | Visitar/seleccionar operador BI. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) override | Visitar/seleccionar operador BDC. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) override | Visitar/seleccionar operador B. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) override | Visitar/seleccionar operador b. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) override | Visitar/seleccionar operador B*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) override | Visitar/seleccionar operador b*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) override | Visitar/seleccionar operador '. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) override | Visitar/seleccionar operador ''. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) override | Visitar/seleccionar operador f*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) override | Visitar/seleccionar operador f. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) override | Visitar/seleccionar operador F. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) override | Visitar/seleccionar operador g. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) override | Visitar/seleccionar operador G. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) override | Visitar/seleccionar operador gs. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) override | Visitar/seleccionar operador h. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) override | Visitar/seleccionar operador i. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) override | Visitar/seleccionar operador ID. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) override | Visitar/seleccionar operador J. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) override | Visitar/seleccionar operador k. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) override | Visitar/seleccionar operador K. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) override | Visitar/seleccionar operador l. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) override | Visitar/seleccionar operador m. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) override | Visitar/seleccionar operador M. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) override | Visitar/seleccionar operador MP. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) override | Visitar/seleccionar operador n. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) override | Visitar/seleccionar operador q. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) override | Visitar/seleccionar operador Q. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) override | Visitar/seleccionar operador re. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) override | Visitar/seleccionar operador rg. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) override | Visitar/seleccionar operador RG. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) override | Visitar/seleccionar operador ri. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) override | Visitar/seleccionar operador s. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) override | Visitar/seleccionar operador S. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) override | Visitar/seleccionar operador sc. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) override | Visitar/seleccionar operador SC. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) override | Visitar/seleccionar operador scn. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) override | Visitar/seleccionar operador SCN. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) override | Visitar/seleccionar operador sh. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) override | Visitar/seleccionar operador T*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) override | Visitar/seleccionar operador Tc. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) override | Visitar/seleccionar operador Td. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) override | Visitar/seleccionar operador TD. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) override | Visitar/seleccionar operador Tf. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) override | Visitar/seleccionar operador Tj. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) override | Visitar/seleccionar operador TJ. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) override | Visitar/seleccionar operador TL. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) override | Visitar/seleccionar operador Tm. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) override | Visitar/seleccionar operador Tr. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) override | Visitar/seleccionar operador Ts. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) override | Visitar/seleccionar operador Tw. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) override | Visitar/seleccionar operador Tz. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) override | Visitar/seleccionar operador v. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) override | Visitar/seleccionar operador W*. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) override | Visitar/seleccionar operador w. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) override | Visitar/seleccionar operador W. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) override | Visitar/seleccionar operador y. |
| [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) override | Visitar/seleccionar cualquier operador de texto operador. |
## Ver también

* Class [IOperatorSelector](../ioperatorselector/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
