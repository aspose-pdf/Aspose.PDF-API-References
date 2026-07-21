---
title: "Clase System::Globalization::NumberFormatInfo"
linktitle: "NumberFormatInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::NumberFormatInfo. Contiene información sobre cómo formatear números. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1900
url: /es/cpp/system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Contiene información sobre cómo formatear números. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona la información de formato. |
| [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Obtiene el número de dígitos decimales de la moneda. |
| [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Obtiene el separador decimal de la moneda. |
| [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Obtiene el separador de grupo de la moneda. |
| [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Obtiene el número de dígitos decimales de la moneda por grupo. |
| [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Obtiene el patrón negativo de la moneda. |
| [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Obtiene el patrón positivo de la moneda. |
| [get_CurrencySymbol](./get_currencysymbol/)() const | Obtiene el símbolo de la moneda. |
| static [get_CurrentInfo](./get_currentinfo/)() | Obtiene la información de formato numérico definida por la cultura del subproceso actual. |
| [get_DigitSubstitution](./get_digitsubstitution/)() const | Obtiene un valor que especifica cómo mostrar la forma de un dígito. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Obtiene la información de formato numérico definida por la cultura invariante. |
| [get_IsReadOnly](./get_isreadonly/)() const | Comprueba si el formato es de solo lectura. |
| [get_NaNSymbol](./get_nansymbol/)() const | Obtiene el símbolo de No es un Número. |
| [get_NativeDigits](./get_nativedigits/)() const | Obtiene los símbolos de dígitos (0 al 9). |
| [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Obtiene el símbolo de infinito negativo. |
| [get_NegativeSign](./get_negativesign/)() const | Obtiene el signo negativo. |
| [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Obtiene el número de dígitos decimales. |
| [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Obtiene el separador decimal. |
| [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Obtiene el separador de grupos de números. |
| [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Obtiene la cantidad de dígitos por grupo. |
| [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Obtiene el patrón negativo de número. |
| [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Obtiene el número de lugares decimales en valores de porcentaje. |
| [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Obtiene el separador decimal en valores de porcentaje. |
| [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Obtiene el separador de grupos en valores de porcentaje. |
| [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Obtiene la cantidad de dígitos por grupo de valores de porcentaje. |
| [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Obtiene el patrón negativo de porcentaje. |
| [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Obtiene el patrón positivo de porcentaje. |
| [get_PercentSymbol](./get_percentsymbol/)() const | Obtiene el símbolo de porcentaje. |
| [get_PerMilleSymbol](./get_permillesymbol/)() const | Obtiene el símbolo de por mil. |
| [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Obtiene el símbolo de infinito positivo. |
| [get_PositiveSign](./get_positivesign/)() const | Obtiene el signo positivo. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Obtiene el formateador de tipo específico. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Obtiene el formateador asociado con el proveedor de formato. |
| [NumberFormatInfo](./numberformatinfo/)() | Constructor predeterminado (invariante [NumberFormatInfo](./)). |
| [operator=](./operator=/)(const NumberFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(NumberFormatInfoPtr) | Obtiene la versión de solo lectura del formateador. |
| [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Establece el número de dígitos decimales de la moneda. |
| [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const String\&) | Establece el separador decimal de la moneda. |
| [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const String\&) | Establece el separador de grupo de la moneda. |
| [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const ArrayPtr\<int\>\&) | Establece el número de dígitos decimales de la moneda por grupo. |
| [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Establece el patrón negativo de la moneda. |
| [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Establece el patrón positivo de la moneda. |
| [set_CurrencySymbol](./set_currencysymbol/)(const String\&) | Establece el símbolo de la moneda. |
| [set_DigitSubstitution](./set_digitsubstitution/)(DigitShapes) | Establece un valor que especifica cómo mostrar la forma de un dígito. |
| [set_NaNSymbol](./set_nansymbol/)(const String\&) | Establece el símbolo Not-a-Number. |
| [set_NativeDigits](./set_nativedigits/)(const ArrayPtr\<String\>\&) | Establece los símbolos de dígitos (0 a 9). |
| [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const String\&) | Establece el símbolo de infinito negativo. |
| [set_NegativeSign](./set_negativesign/)(const String\&) | Establece el signo negativo. |
| [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Establece el número de dígitos decimales. |
| [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const String\&) | Establece el separador decimal. |
| [set_NumberGroupSeparator](./set_numbergroupseparator/)(const String\&) | Establece el separador de grupo numérico. |
| [set_NumberGroupSizes](./set_numbergroupsizes/)(const ArrayPtr\<int\>\&) | Establece el número de dígitos por grupo. |
| [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Establece el patrón negativo de número. |
| [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Establece el número de lugares decimales en los valores de porcentaje. |
| [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const String\&) | Establece el separador decimal en los valores de porcentaje. |
| [set_PercentGroupSeparator](./set_percentgroupseparator/)(const String\&) | Establece el separador de grupo en los valores de porcentaje. |
| [set_PercentGroupSizes](./set_percentgroupsizes/)(const ArrayPtr\<int\>\&) | Establece el número de dígitos por grupo de valores de porcentaje. |
| [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Establece el patrón negativo de porcentaje. |
| [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Establece el patrón positivo de porcentaje. |
| [set_PercentSymbol](./set_percentsymbol/)(const String\&) | Establece el símbolo de porcentaje. |
| [set_PerMilleSymbol](./set_permillesymbol/)(const String\&) | Establece el símbolo de permil. |
| [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const String\&) | Establece el símbolo de infinito positivo. |
| [set_PositiveSign](./set_positivesign/)(const String\&) | Establece el signo positivo. |
## Ver también

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
