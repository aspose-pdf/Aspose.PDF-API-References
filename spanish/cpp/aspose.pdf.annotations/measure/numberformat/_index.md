---
title: "Aspose::Pdf::Annotations::Measure::NumberFormat class"
linktitle: "NumberFormat"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::Measure::NumberFormat class. Formato numérico para medida en C++."
type: docs
weight: 2000
url: /es/cpp/aspose.pdf.annotations/measure/numberformat/
---
## NumberFormat class


Formato numérico para medida.

```cpp
class NumberFormat : public System::Object
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [FractionStyle](./fractionstyle/) | Valor que indica de qué manera se muestran los valores fraccionarios. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AfterText](./get_aftertext/)() | [Text](../../../aspose.pdf.text/) que se concatenará después de la etiqueta. |
| [get_BeforeText](./get_beforetext/)() | [Text](../../../aspose.pdf.text/) que se concatenará a la izquierda de la etiqueta. |
| [get_ConvresionFactor](./get_convresionfactor/)() | El factor de conversión utilizado para multiplicar un valor en unidades parciales del elemento anterior de la matriz de formato numérico para obtener un valor en las unidades de este formato numérico. |
| [get_Denominator](./get_denominator/)() | Si FractionDisplayment es ShowAsFraction, este valor es el denominador de la fracción. El valor predeterminado es 16. |
| [get_ForceDenominator](./get_forcedenominator/)() | Si FractionDisplayment es ShowAsFraction, este valor determina si la fracción se reduce o no. Si el valor es verdadero, la fracción puede no reducirse. |
| [get_FractionDisplayment](./get_fractiondisplayment/)() | De qué manera se muestran los valores fraccionarios. |
| [get_FractionSeparator](./get_fractionseparator/)() | [Text](../../../aspose.pdf.text/) que se usará como posición decimal al mostrar valores numéricos. Una cadena vacía indica que se usará el valor predeterminado. El predeterminado es el carácter de punto. |
| [get_Precision](./get_precision/)() | Si FractionDisplayment es ShowAsDecimal, este valor es la precisión del valor fraccionario; debe ser múltiplo de 10. El valor predeterminado es 100. |
| [get_ThousandsSeparator](./get_thousandsseparator/)() | [Text](../../../aspose.pdf.text/) que se usará entre los órdenes de miles al mostrar valores numéricos. Una cadena vacía indica que no se añadirá texto. El predeterminado es la coma. |
| [get_UnitLabel](./get_unitlabel/)() | Una cadena de texto que especifica una etiqueta para mostrar las unidades. |
| [NumberFormat](./numberformat/)(const System::SharedPtr\<Measure\>\&) | Constructor para la clase [NumberFormat](./). |
| [set_AfterText](./set_aftertext/)(const System::String\&) | [Text](../../../aspose.pdf.text/) que se concatenará después de la etiqueta. |
| [set_BeforeText](./set_beforetext/)(const System::String\&) | [Text](../../../aspose.pdf.text/) que se concatenará a la izquierda de la etiqueta. |
| [set_ConvresionFactor](./set_convresionfactor/)(double) | El factor de conversión utilizado para multiplicar un valor en unidades parciales del elemento anterior de la matriz de formato numérico para obtener un valor en las unidades de este formato numérico. |
| [set_Denominator](./set_denominator/)(int32_t) | Si FractionDisplayment es ShowAsFraction, este valor es el denominador de la fracción. El valor predeterminado es 16. |
| [set_ForceDenominator](./set_forcedenominator/)(bool) | Si FractionDisplayment es ShowAsFraction, este valor determina si la fracción se reduce o no. Si el valor es verdadero, la fracción puede no reducirse. |
| [set_FractionDisplayment](./set_fractiondisplayment/)(Measure::NumberFormat::FractionStyle) | De qué manera se muestran los valores fraccionarios. |
| [set_FractionSeparator](./set_fractionseparator/)(const System::String\&) | [Text](../../../aspose.pdf.text/) que se usará como posición decimal al mostrar valores numéricos. Una cadena vacía indica que se usará el valor predeterminado. El predeterminado es el carácter de punto. |
| [set_Precision](./set_precision/)(int32_t) | Si FractionDisplayment es ShowAsDecimal, este valor es la precisión del valor fraccionario; debe ser múltiplo de 10. El valor predeterminado es 100. |
| [set_ThousandsSeparator](./set_thousandsseparator/)(const System::String\&) | [Text](../../../aspose.pdf.text/) que se usará entre los órdenes de miles al mostrar valores numéricos. Una cadena vacía indica que no se añadirá texto. El predeterminado es la coma. |
| [set_UnitLabel](./set_unitlabel/)(const System::String\&) | Una cadena de texto que especifica una etiqueta para mostrar las unidades. |
## Ver también

* Class [Object](../../../system/object/)
* Class [Measure](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
