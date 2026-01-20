---
title: System::Globalization::NumberFormatInfo class
linktitle: NumberFormatInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::NumberFormatInfo class. Holds information on how to format numbers. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1900
url: /cpp/system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Holds information on how to format numbers. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones format info. |
| [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Gets number of currency decimal digits. |
| [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Gets currency decimal separator. |
| [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Gets currency group separator. |
| [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Gets number of currency decimal digits per group. |
| [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Gets currency negative pattern. |
| [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Gets currency positive pattern. |
| [get_CurrencySymbol](./get_currencysymbol/)() const | Gets currency symbol. |
| static [get_CurrentInfo](./get_currentinfo/)() | Gets current thread culture-defined number format info. |
| [get_DigitSubstitution](./get_digitsubstitution/)() const | Gets a value that specifies how to display shape of a digit. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Gets invariant culture-defined number format info. |
| [get_IsReadOnly](./get_isreadonly/)() const | Checks if format is read-only. |
| [get_NaNSymbol](./get_nansymbol/)() const | Gets Not-a-Number symbol. |
| [get_NativeDigits](./get_nativedigits/)() const | Gets digits symbols (0 through 9). |
| [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Gets negative infinity symbol. |
| [get_NegativeSign](./get_negativesign/)() const | Gets negative sign. |
| [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Gets number of decimal digits. |
| [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Gets decimal separator. |
| [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Gets number group separator. |
| [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Gets numbers of digits per group. |
| [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Gets number negative pattern. |
| [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Gets number of decimal places in percent values. |
| [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Gets decimal separator in percent values. |
| [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Gets group separator in percent values. |
| [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Gets numbers of digits per percent value group. |
| [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Gets percent negative pattern. |
| [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Gets percent positive pattern. |
| [get_PercentSymbol](./get_percentsymbol/)() const | Gets percent symbol. |
| [get_PerMilleSymbol](./get_permillesymbol/)() const | Gets permille symbol. |
| [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Gets positive infinity symbol. |
| [get_PositiveSign](./get_positivesign/)() const | Gets positive sign. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Gets formatter of specific type. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Gets formatter associated with format provider. |
| [NumberFormatInfo](./numberformatinfo/)() | Default constructor (invariant [NumberFormatInfo](./)). |
| [operator=](./operator=/)(const NumberFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(NumberFormatInfoPtr) | Gets read-only version of formatter. |
| [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Sets number of currency decimal digits. |
| [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const String\&) | Sets currency decimal separator. |
| [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const String\&) | Sets currency group separator. |
| [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const ArrayPtr\<int\>\&) | Sets number of currency decimal digits per group. |
| [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Sets currency negative pattern. |
| [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Sets currency positive pattern. |
| [set_CurrencySymbol](./set_currencysymbol/)(const String\&) | Sets currency symbol. |
| [set_DigitSubstitution](./set_digitsubstitution/)(DigitShapes) | Sets a value that specifies how to display shape of a digit. |
| [set_NaNSymbol](./set_nansymbol/)(const String\&) | Sets Not-a-Number symbol. |
| [set_NativeDigits](./set_nativedigits/)(const ArrayPtr\<String\>\&) | Sets digits symbols (0 through 9). |
| [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const String\&) | Sets negative infinity symbol. |
| [set_NegativeSign](./set_negativesign/)(const String\&) | Sets negative sign. |
| [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Sets number of decimal digits. |
| [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const String\&) | Sets decimal separator. |
| [set_NumberGroupSeparator](./set_numbergroupseparator/)(const String\&) | Sets number group separator. |
| [set_NumberGroupSizes](./set_numbergroupsizes/)(const ArrayPtr\<int\>\&) | Sets numbers of digits per group. |
| [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Sets number negative pattern. |
| [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Sets number of decimal places in percent values. |
| [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const String\&) | Sets decimal separator in percent values. |
| [set_PercentGroupSeparator](./set_percentgroupseparator/)(const String\&) | Sets group separator in percent values. |
| [set_PercentGroupSizes](./set_percentgroupsizes/)(const ArrayPtr\<int\>\&) | Sets numbers of digits per percent value group. |
| [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Sets percent negative pattern. |
| [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Sets percent positive pattern. |
| [set_PercentSymbol](./set_percentsymbol/)(const String\&) | Sets percent symbol. |
| [set_PerMilleSymbol](./set_permillesymbol/)(const String\&) | Sets permille symbol. |
| [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const String\&) | Sets positive infinity symbol. |
| [set_PositiveSign](./set_positivesign/)(const String\&) | Sets positive sign. |
## See Also

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
