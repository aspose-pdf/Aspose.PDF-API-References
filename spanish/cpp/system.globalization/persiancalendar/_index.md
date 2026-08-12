---
title: "Clase System::Globalization::PersianCalendar"
linktitle: "PersianCalendar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::PersianCalendar. Calendario persa. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.globalization/persiancalendar/
---
## PersianCalendar class


Calendario persa. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class PersianCalendar : public System::Globalization::Calendar
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Información RTTI. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Obtiene el tipo de algoritmo. |
| [get_Eras](./get_eras/)() const override | Obtiene la lista de eras existentes en el calendario. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Punto máximo en el tiempo que es compatible con el calendario. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Punto mínimo en el tiempo que es compatible con el calendario. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Obtiene el día de la semana para el punto de tiempo especificado. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Obtiene el número de días en un mes específico. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Información RTTI. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Obtiene el número de días en un año específico. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Obtiene el número de días en un año específico. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtiene el mes intercalado para el año especificado. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Obtiene el mes intercalado para el año especificado. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Obtiene el número de meses en el año especificado. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Obtiene el número de meses en el año especificado. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Comprueba si el día es bisiesto. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Comprueba si el día es bisiesto. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Comprueba si el mes es intercalado. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Comprueba si el mes es intercalado. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Comprueba si el año es bisiesto. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Comprueba si el año es bisiesto. |
| [PersianCalendar](./persiancalendar/)() | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [PersianEra](./persianera/) | Era persa actual. |
## Ver también

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
