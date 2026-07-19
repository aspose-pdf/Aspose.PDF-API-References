---
title: "класс Aspose::Pdf::Annotations::Measure::NumberFormat"
linktitle: "NumberFormat"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::Measure::NumberFormat class. Формат числа для измерения в C++."
type: docs
weight: 2000
url: /ru/cpp/aspose.pdf.annotations/measure/numberformat/
---
## NumberFormat class


Формат числа для измерения.

```cpp
class NumberFormat : public System::Object
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [FractionStyle](./fractionstyle/) | Значение, указывающее, каким образом отображаются дробные значения. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_AfterText](./get_aftertext/)() | [Text](../../../aspose.pdf.text/) который будет добавлен после метки. |
| [get_BeforeText](./get_beforetext/)() | [Text](../../../aspose.pdf.text/) который будет добавлен слева от метки. |
| [get_ConvresionFactor](./get_convresionfactor/)() | Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива форматов чисел, чтобы получить значение в единицах этого формата числа. |
| [get_Denominator](./get_denominator/)() | Если FractionDisplayment имеет значение ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16. |
| [get_ForceDenominator](./get_forcedenominator/)() | Если FractionDisplayment имеет значение ShowAsFraction, это значение определяет, будет ли дробь сокращена. Если значение истинно, дробь может не быть сокращена. |
| [get_FractionDisplayment](./get_fractiondisplayment/)() | Как отображаются дробные значения. |
| [get_FractionSeparator](./get_fractionseparator/)() | [Text](../../../aspose.pdf.text/) который будет использоваться в качестве десятичного разделителя при отображении числовых значений. Пустая строка указывает, что будет использовано значение по умолчанию. По умолчанию — точка. |
| [get_Precision](./get_precision/)() | Если FractionDisplayment имеет значение ShowAsDecimal, это значение является точностью дробного значения; оно должно быть кратным 10. По умолчанию — 100. |
| [get_ThousandsSeparator](./get_thousandsseparator/)() | [Text](../../../aspose.pdf.text/) который будет использоваться между разрядами тысяч при отображении числовых значений. Пустая строка указывает, что текст добавлен не будет. По умолчанию — запятая. |
| [get_UnitLabel](./get_unitlabel/)() | Текстовая строка, указывающая метку для отображения единиц. |
| [NumberFormat](./numberformat/)(const System::SharedPtr\<Measure\>\&) | Конструктор класса [NumberFormat](./). |
| [set_AfterText](./set_aftertext/)(const System::String\&) | [Text](../../../aspose.pdf.text/) который будет добавлен после метки. |
| [set_BeforeText](./set_beforetext/)(const System::String\&) | [Text](../../../aspose.pdf.text/) который будет добавлен слева от метки. |
| [set_ConvresionFactor](./set_convresionfactor/)(double) | Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива форматов чисел, чтобы получить значение в единицах этого формата числа. |
| [set_Denominator](./set_denominator/)(int32_t) | Если FractionDisplayment имеет значение ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16. |
| [set_ForceDenominator](./set_forcedenominator/)(bool) | Если FractionDisplayment имеет значение ShowAsFraction, это значение определяет, будет ли дробь сокращена. Если значение истинно, дробь может не быть сокращена. |
| [set_FractionDisplayment](./set_fractiondisplayment/)(Measure::NumberFormat::FractionStyle) | Как отображаются дробные значения. |
| [set_FractionSeparator](./set_fractionseparator/)(const System::String\&) | [Text](../../../aspose.pdf.text/) который будет использоваться в качестве десятичного разделителя при отображении числовых значений. Пустая строка указывает, что будет использовано значение по умолчанию. По умолчанию — точка. |
| [set_Precision](./set_precision/)(int32_t) | Если FractionDisplayment имеет значение ShowAsDecimal, это значение является точностью дробного значения; оно должно быть кратным 10. По умолчанию — 100. |
| [set_ThousandsSeparator](./set_thousandsseparator/)(const System::String\&) | [Text](../../../aspose.pdf.text/) который будет использоваться между разрядами тысяч при отображении числовых значений. Пустая строка указывает, что текст добавлен не будет. По умолчанию — запятая. |
| [set_UnitLabel](./set_unitlabel/)(const System::String\&) | Текстовая строка, указывающая метку для отображения единиц. |
## См. также

* Class [Object](../../../system/object/)
* Class [Measure](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
