---
title: "Clase System::Globalization::UmAlQuraCalendar"
linktitle: "UmAlQuraCalendar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::UmAlQuraCalendar. Calendario Um Al Qura. No implementado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3000
url: /es/cpp/system.globalization/umalquracalendar/
---
## UmAlQuraCalendar class


Calendario Um Al Qura. No implementado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
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
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtiene el mes intercalado para el año especificado. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Información RTTI. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Comprueba si el día es bisiesto. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Comprueba si el día es bisiesto. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Comprueba si el mes es intercalado. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Comprueba si el mes es intercalado. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Comprueba si el año es bisiesto. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Comprueba si el año es bisiesto. |
| [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | Establece el último año que puede representarse con dos dígitos. |
| [UmAlQuraCalendar](./umalquracalendar/)() | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | Era actual de UmAlQura. |
## Ver también

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
