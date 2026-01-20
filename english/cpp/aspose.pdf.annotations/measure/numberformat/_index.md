---
title: Aspose::Pdf::Annotations::Measure::NumberFormat class
linktitle: NumberFormat
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::Measure::NumberFormat class. Number format for measure in C++.'
type: docs
weight: 2000
url: /cpp/aspose.pdf.annotations/measure/numberformat/
---
## NumberFormat class


Number format for measure.

```cpp
class NumberFormat : public System::Object
```

## Enums

| Enum | Description |
| --- | --- |
| [FractionStyle](./fractionstyle/) | Value which indicates in which manner fraction values are displayed. |
## Methods

| Method | Description |
| --- | --- |
| [get_AfterText](./get_aftertext/)() | [Text](../../../aspose.pdf.text/) that shall be concatenated after the label. |
| [get_BeforeText](./get_beforetext/)() | [Text](../../../aspose.pdf.text/) that shall be concatenated to the left of the label. |
| [get_ConvresionFactor](./get_convresionfactor/)() | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [get_Denominator](./get_denominator/)() | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16. |
| [get_ForceDenominator](./get_forcedenominator/)() | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced. |
| [get_FractionDisplayment](./get_fractiondisplayment/)() | In what manner fractional values are displayed. |
| [get_FractionSeparator](./get_fractionseparator/)() | [Text](../../../aspose.pdf.text/) that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character. |
| [get_Precision](./get_precision/)() | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100. |
| [get_ThousandsSeparator](./get_thousandsseparator/)() | [Text](../../../aspose.pdf.text/) that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma. |
| [get_UnitLabel](./get_unitlabel/)() | A text string specifying a label for displaying the units. |
| [NumberFormat](./numberformat/)(System::SharedPtr\<Measure\>) | Constructor for [NumberFormat](./) class. |
| [set_AfterText](./set_aftertext/)(System::String) | [Text](../../../aspose.pdf.text/) that shall be concatenated after the label. |
| [set_BeforeText](./set_beforetext/)(System::String) | [Text](../../../aspose.pdf.text/) that shall be concatenated to the left of the label. |
| [set_ConvresionFactor](./set_convresionfactor/)(double) | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [set_Denominator](./set_denominator/)(int32_t) | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16. |
| [set_ForceDenominator](./set_forcedenominator/)(bool) | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced. |
| [set_FractionDisplayment](./set_fractiondisplayment/)(Measure::NumberFormat::FractionStyle) | In what manner fractional values are displayed. |
| [set_FractionSeparator](./set_fractionseparator/)(System::String) | [Text](../../../aspose.pdf.text/) that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character. |
| [set_Precision](./set_precision/)(int32_t) | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100. |
| [set_ThousandsSeparator](./set_thousandsseparator/)(System::String) | [Text](../../../aspose.pdf.text/) that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma. |
| [set_UnitLabel](./set_unitlabel/)(System::String) | A text string specifying a label for displaying the units. |
## See Also

* Class [Object](../../../system/object/)
* Class [Measure](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
