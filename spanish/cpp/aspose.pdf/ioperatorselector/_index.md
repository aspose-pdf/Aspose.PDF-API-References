---
title: "Aspose::Pdf::IOperatorSelector clase"
linktitle: "IOperatorSelector"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::IOperatorSelector clase. Define Visitor para visitar diferentes operadores pdf en C++."
type: docs
weight: 8900
url: /es/cpp/aspose.pdf/ioperatorselector/
---
## IOperatorSelector class


Define Visitor para visitar diferentes operadores pdf.

```cpp
class IOperatorSelector : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Fill\>\&) | Visitar/seleccionar operador f. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ObsoleteFill\>\&) | Visitar/seleccionar operador F. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFill\>\&) | Visitar/seleccionar operador f*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGrayStroke\>\&) | Visitar/seleccionar operador G. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGray\>\&) | Visitar/seleccionar operador g. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GS\>\&) | Visitar/seleccionar operador gs. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePath\>\&) | Visitar/seleccionar operador h. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetFlat\>\&) | Visitar/seleccionar operador i. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ID\>\&) | Visitar/seleccionar operador ID. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorRenderingIntent\>\&) | Visitar/seleccionar operador ri. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineCap\>\&) | Visitar/seleccionar operador J. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetMiterLimit\>\&) | Visitar/seleccionar operador M. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MP\>\&) | Visitar/seleccionar operador MP. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EndPath\>\&) | Visitar/seleccionar operador n. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GSave\>\&) | Visitar/seleccionar operador q. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::GRestore\>\&) | Visitar/seleccionar operador Q. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Re\>\&) | Visitar/seleccionar operador re. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColorStroke\>\&) | Visitar/seleccionar operador RG. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetRGBColor\>\&) | Visitar/seleccionar operador rg. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColorStroke\>\&) | Visitar/seleccionar operador K. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCMYKColor\>\&) | Visitar/seleccionar operador k. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::LineTo\>\&) | Visitar/seleccionar operador l. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTo\>\&) | Visitar/seleccionar operador m. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetWordSpacing\>\&) | Visitar/seleccionar operador Tw. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathStroke\>\&) | Visitar/seleccionar operador s. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPositionSetLeading\>\&) | Visitar/seleccionar operador TD. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SelectFont\>\&) | Visitar/seleccionar operador Tf. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShowText\>\&) | Visitar/seleccionar operador Tj. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetGlyphsPositionShowText\>\&) | Visitar/seleccionar operador TJ. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextLeading\>\&) | Visitar/seleccionar operador TL. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextMatrix\>\&) | Visitar/seleccionar operador Tm. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRenderingMode\>\&) | Visitar/seleccionar operador Tr. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetTextRise\>\&) | Visitar/seleccionar operador Ts. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Stroke\>\&) | Visitar/seleccionar operador S. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorStroke\>\&) | Visitar/seleccionar operador SC. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColor\>\&) | Visitar/seleccionar operador sc. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColorStroke\>\&) | Visitar/seleccionar operador SCN. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetAdvancedColor\>\&) | Visitar/seleccionar operador scn. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ShFill\>\&) | Visitar/seleccionar operador sh. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLine\>\&) | Visitar/seleccionar operador T*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharacterSpacing\>\&) | Visitar/seleccionar operador Tc. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveTextPosition\>\&) | Visitar/seleccionar operador Td. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo2\>\&) | Visitar/seleccionar operador y. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOClip\>\&) | Visitar/seleccionar operador W*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetHorizontalTextScaling\>\&) | Visitar/seleccionar operador Tz. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo1\>\&) | Visitar/seleccionar operador v. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Clip\>\&) | Visitar/seleccionar operador W. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineWidth\>\&) | Visitar/seleccionar operador w. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetLineJoin\>\&) | Visitar/seleccionar operador j. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EX\>\&) | Visitar/seleccionar operador EX. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ET\>\&) | Visitar/seleccionar operador ET. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EMC\>\&) | Visitar/seleccionar operador EMC. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EI\>\&) | Visitar/seleccionar operador EI. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::DP\>\&) | Visitar/seleccionar operador DP. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::Do\>\&) | Visitar/seleccionar operador Do. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetDash\>\&) | Visitar/seleccionar operador d. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidth\>\&) | Visitar/seleccionar operador d0. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetCharWidthBoundingBox\>\&) | Visitar/seleccionar operador d1. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpaceStroke\>\&) | Visitar/seleccionar operador CS. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetColorSpace\>\&) | Visitar/seleccionar operador cs. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ConcatenateMatrix\>\&) | Visitar/seleccionar operador cm. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::CurveTo\>\&) | Visitar/seleccionar operador c. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BX\>\&) | Visitar/seleccionar operador BX. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BT\>\&) | Visitar/seleccionar operador BT. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BMC\>\&) | Visitar/seleccionar operador BMC. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BI\>\&) | Visitar/seleccionar operador BI. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::BDC\>\&) | Visitar/seleccionar operador BDC. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::FillStroke\>\&) | Visitar/seleccionar operador B. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathFillStroke\>\&) | Visitar/seleccionar operador b. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::EOFillStroke\>\&) | Visitar/seleccionar operador B*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::ClosePathEOFillStroke\>\&) | Visitar/seleccionar operador b*. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::MoveToNextLineShowText\>\&) | Visitar/seleccionar operador '. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::SetSpacingMoveToNextLineShowText\>\&) | Visitar/seleccionar operador ''. |
| virtual [Visit](./visit/)(const System::SharedPtr\<Operators::TextOperator\>\&) | Visitar/seleccionar cualquier operador de texto operador. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
