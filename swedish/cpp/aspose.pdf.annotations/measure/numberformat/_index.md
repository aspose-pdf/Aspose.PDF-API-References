---
title: "Aspose::Pdf::Annotations::Measure::NumberFormat klass"
linktitle: "NumberFormat"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::Measure::NumberFormat klass. Numeriskt format för mätning i C++."
type: docs
weight: 2000
url: /sv/cpp/aspose.pdf.annotations/measure/numberformat/
---
## NumberFormat class


Numeriskt format för mätning.

```cpp
class NumberFormat : public System::Object
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [FractionStyle](./fractionstyle/) | Värde som anger på vilket sätt bråkvärden visas. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AfterText](./get_aftertext/)() | [Text](../../../aspose.pdf.text/) som ska konkateneras efter etiketten. |
| [get_BeforeText](./get_beforetext/)() | [Text](../../../aspose.pdf.text/) som ska konkateneras till vänster om etiketten. |
| [get_ConvresionFactor](./get_convresionfactor/)() | Konversionsfaktorn som används för att multiplicera ett värde i delvisa enheter av föregående element i numerisk formatmatris för att erhålla ett värde i enheterna för detta numeriska format. |
| [get_Denominator](./get_denominator/)() | Om FractionDisplayment är ShowAsFraction är detta värde nämnaren i bråket. Standardvärdet är 16. |
| [get_ForceDenominator](./get_forcedenominator/)() | Om FractionDisplayment är ShowAsFraction bestämmer detta värde om bråket ska reduceras eller inte. Om värdet är true får bråket inte reduceras. |
| [get_FractionDisplayment](./get_fractiondisplayment/)() | På vilket sätt bråkvärden visas. |
| [get_FractionSeparator](./get_fractionseparator/)() | [Text](../../../aspose.pdf.text/) som ska användas som decimalposition vid visning av numeriska värden. En tom sträng indikerar att standardvärdet ska användas. Standard är punkttecken. |
| [get_Precision](./get_precision/)() | Om FractionDisplayment är ShowAsDecimal är detta värde precisionen för bråkvärdet; det ska vara en multipel av 10. Standard är 100. |
| [get_ThousandsSeparator](./get_thousandsseparator/)() | [Text](../../../aspose.pdf.text/) som ska användas mellan tusental i visning av numeriska värden. En tom sträng indikerar att ingen text ska läggas till. Standard är komma. |
| [get_UnitLabel](./get_unitlabel/)() | En textsträng som specificerar en etikett för att visa enheterna. |
| [NumberFormat](./numberformat/)(const System::SharedPtr\<Measure\>\&) | Konstruktor för klassen [NumberFormat](./). |
| [set_AfterText](./set_aftertext/)(const System::String\&) | [Text](../../../aspose.pdf.text/) som ska konkateneras efter etiketten. |
| [set_BeforeText](./set_beforetext/)(const System::String\&) | [Text](../../../aspose.pdf.text/) som ska konkateneras till vänster om etiketten. |
| [set_ConvresionFactor](./set_convresionfactor/)(double) | Konversionsfaktorn som används för att multiplicera ett värde i delvisa enheter av föregående element i numerisk formatmatris för att erhålla ett värde i enheterna för detta numeriska format. |
| [set_Denominator](./set_denominator/)(int32_t) | Om FractionDisplayment är ShowAsFraction är detta värde nämnaren i bråket. Standardvärdet är 16. |
| [set_ForceDenominator](./set_forcedenominator/)(bool) | Om FractionDisplayment är ShowAsFraction bestämmer detta värde om bråket ska reduceras eller inte. Om värdet är true får bråket inte reduceras. |
| [set_FractionDisplayment](./set_fractiondisplayment/)(Measure::NumberFormat::FractionStyle) | På vilket sätt bråkvärden visas. |
| [set_FractionSeparator](./set_fractionseparator/)(const System::String\&) | [Text](../../../aspose.pdf.text/) som ska användas som decimalposition vid visning av numeriska värden. En tom sträng indikerar att standardvärdet ska användas. Standard är punkttecken. |
| [set_Precision](./set_precision/)(int32_t) | Om FractionDisplayment är ShowAsDecimal är detta värde precisionen för bråkvärdet; det ska vara en multipel av 10. Standard är 100. |
| [set_ThousandsSeparator](./set_thousandsseparator/)(const System::String\&) | [Text](../../../aspose.pdf.text/) som ska användas mellan tusental i visning av numeriska värden. En tom sträng indikerar att ingen text ska läggas till. Standard är komma. |
| [set_UnitLabel](./set_unitlabel/)(const System::String\&) | En textsträng som specificerar en etikett för att visa enheterna. |
## Se även

* Class [Object](../../../system/object/)
* Class [Measure](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
