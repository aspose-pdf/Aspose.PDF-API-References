---
title: "Clase System::Globalization::ChineseLunisolarCalendar"
linktitle: "ChineseLunisolarCalendar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::ChineseLunisolarCalendar. Calendario lunisolar chino. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar class


Calendario lunisolar chino. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | Constructor predeterminado. |
| [Clone](./clone/)() override | Información RTTI. |
| [get_Eras](./get_eras/)() const override | Obtiene la lista de eras existentes en el calendario. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Punto máximo en el tiempo que es compatible con el calendario. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Punto mínimo en el tiempo que es compatible con el calendario. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Obtiene el número de días en un mes específico. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtiene el número de días en un mes específico. |
| [GetEra](./getera/)(DateTime) const override | Obtiene la era para el punto de tiempo especificado. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtiene el mes intercalado para el año especificado. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Obtiene el mes intercalado para el año especificado. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Obtiene el número de meses en el año especificado. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Información RTTI. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Comprueba si el día es bisiesto. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Comprueba si el día es bisiesto. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Comprueba si el mes es intercalado. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Comprueba si el mes es intercalado. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Comprueba si el año es bisiesto. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Comprueba si el año es bisiesto. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | Era china actual. |
## Ver también

* Class [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
