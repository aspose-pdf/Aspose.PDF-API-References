---
title: "System::Globalization::NumberFormatInfo класс"
linktitle: "NumberFormatInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::NumberFormatInfo класс. Содержит информацию о том, как форматировать числа. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1900
url: /ru/cpp/system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Содержит информацию о том, как форматировать числа. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонирует информацию о формате. |
| [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Возвращает количество десятичных знаков валюты. |
| [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Возвращает десятичный разделитель валюты. |
| [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Возвращает разделитель групп валюты. |
| [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Возвращает количество десятичных знаков валюты в группе. |
| [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Возвращает отрицательный шаблон валюты. |
| [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Возвращает положительный шаблон валюты. |
| [get_CurrencySymbol](./get_currencysymbol/)() const | Возвращает символ валюты. |
| static [get_CurrentInfo](./get_currentinfo/)() | Получает информацию о формате числа, определённую текущей культурой потока. |
| [get_DigitSubstitution](./get_digitsubstitution/)() const | Получает значение, которое определяет, как отображать форму цифры. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Получает информацию о формате числа, определённую инвариантной культурой. |
| [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли формат только для чтения. |
| [get_NaNSymbol](./get_nansymbol/)() const | Получает символ Not-a-Number. |
| [get_NativeDigits](./get_nativedigits/)() const | Получает символы цифр (от 0 до 9). |
| [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Получает символ отрицательной бесконечности. |
| [get_NegativeSign](./get_negativesign/)() const | Получает знак минуса. |
| [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Получает количество десятичных знаков. |
| [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Получает десятичный разделитель. |
| [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Получает разделитель групп чисел. |
| [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Получает количество цифр в группе. |
| [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Получает шаблон отрицательного числа. |
| [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Получает количество десятичных знаков в процентных значениях. |
| [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Получает десятичный разделитель в процентных значениях. |
| [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Получает разделитель групп в процентных значениях. |
| [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Получает количество цифр в группе процентных значений. |
| [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Получает шаблон отрицательного процента. |
| [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Получает шаблон положительного процента. |
| [get_PercentSymbol](./get_percentsymbol/)() const | Получает символ процента. |
| [get_PerMilleSymbol](./get_permillesymbol/)() const | Получает символ промилле. |
| [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Получает символ положительной бесконечности. |
| [get_PositiveSign](./get_positivesign/)() const | Получает знак плюса. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Получает форматировщик определённого типа. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Получает форматировщик, связанный с поставщиком формата. |
| [NumberFormatInfo](./numberformatinfo/)() | Конструктор по умолчанию (независимый [NumberFormatInfo](./)). |
| [operator=](./operator=/)(const NumberFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(NumberFormatInfoPtr) | Получает только для чтения версию форматировщика. |
| [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Устанавливает количество десятичных знаков валюты. |
| [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const String\&) | Устанавливает десятичный разделитель валюты. |
| [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const String\&) | Устанавливает разделитель групп валюты. |
| [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const ArrayPtr\<int\>\&) | Устанавливает количество десятичных знаков валюты в группе. |
| [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Устанавливает отрицательный шаблон валюты. |
| [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Устанавливает положительный шаблон валюты. |
| [set_CurrencySymbol](./set_currencysymbol/)(const String\&) | Устанавливает символ валюты. |
| [set_DigitSubstitution](./set_digitsubstitution/)(DigitShapes) | Устанавливает значение, определяющее, как отображать форму цифры. |
| [set_NaNSymbol](./set_nansymbol/)(const String\&) | Устанавливает символ Not-a-Number. |
| [set_NativeDigits](./set_nativedigits/)(const ArrayPtr\<String\>\&) | Устанавливает символы цифр (от 0 до 9). |
| [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const String\&) | Устанавливает символ отрицательной бесконечности. |
| [set_NegativeSign](./set_negativesign/)(const String\&) | Устанавливает знак минуса. |
| [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Устанавливает количество десятичных знаков. |
| [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const String\&) | Устанавливает десятичный разделитель. |
| [set_NumberGroupSeparator](./set_numbergroupseparator/)(const String\&) | Устанавливает разделитель групп чисел. |
| [set_NumberGroupSizes](./set_numbergroupsizes/)(const ArrayPtr\<int\>\&) | Устанавливает количество цифр в группе. |
| [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Устанавливает отрицательный шаблон числа. |
| [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Устанавливает количество десятичных знаков в значениях процентов. |
| [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const String\&) | Устанавливает десятичный разделитель в значениях процентов. |
| [set_PercentGroupSeparator](./set_percentgroupseparator/)(const String\&) | Устанавливает разделитель групп в значениях процентов. |
| [set_PercentGroupSizes](./set_percentgroupsizes/)(const ArrayPtr\<int\>\&) | Устанавливает количество цифр в группе значений процентов. |
| [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Устанавливает отрицательный шаблон процентов. |
| [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Устанавливает положительный шаблон процентов. |
| [set_PercentSymbol](./set_percentsymbol/)(const String\&) | Устанавливает символ процента. |
| [set_PerMilleSymbol](./set_permillesymbol/)(const String\&) | Устанавливает символ промилле. |
| [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const String\&) | Устанавливает символ положительной бесконечности. |
| [set_PositiveSign](./set_positivesign/)(const String\&) | Устанавливает знак плюса. |
## См. также

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
