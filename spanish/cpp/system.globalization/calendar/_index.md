---
title: "System::Globalization::Calendar clase"
linktitle: "Calendar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Globalization::Calendar clase. Calendario que define cómo se manejan, calculan, formatean, etc., las fechas. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.globalization/calendar/
---
## Calendar class


[Calendar](./) which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Calendar : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AddDays](./adddays/)(DateTime, int) const | Agrega días al punto de tiempo. |
| virtual [AddHours](./addhours/)(DateTime, int) const | Agrega horas al punto de tiempo. |
| virtual [AddMilliseconds](./addmilliseconds/)(DateTime, double) const | Agrega milisegundos al punto de tiempo. |
| virtual [AddMinutes](./addminutes/)(DateTime, int) const | Agrega minutos al punto de tiempo. |
| virtual [AddMonths](./addmonths/)(DateTime, int) const | Agrega meses al punto de tiempo. |
| virtual [AddSeconds](./addseconds/)(DateTime, int) const | Agrega segundos al punto de tiempo. |
| virtual [AddWeeks](./addweeks/)(DateTime, int) const | Agrega semanas al punto de tiempo. |
| virtual [AddYears](./addyears/)(DateTime, int) const | Agrega años al punto de tiempo. |
| [Calendar](./calendar/)(const Calendar\&) | Información RTTI. |
| virtual [get_AlgorithmType](./get_algorithmtype/)() const | Obtiene el tipo de algoritmo. |
| [get_CurrentEra](./get_currentera/)() const | Obtiene el índice de la era actual. |
| [get_CurrentEraValue](./get_currenteravalue/)() const | Obtiene el valor de la era actual. |
| virtual [get_Eras](./get_eras/)() const | Obtiene la lista de eras existentes en el calendario. |
| virtual [get_ID](./get_id/)() const | Obtiene el identificador del calendario. |
| [get_IsReadOnly](./get_isreadonly/)() const | Verifica si el calendario es de solo lectura. |
| virtual [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Punto máximo en el tiempo que es compatible con el calendario. |
| virtual [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Punto mínimo en el tiempo que es compatible con el calendario. |
| virtual [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Obtiene el último año que puede representarse con dos dígitos. |
| virtual [GetDayOfMonth](./getdayofmonth/)(DateTime) const | Obtiene el día del mes para el punto de tiempo especificado. |
| virtual [GetDayOfWeek](./getdayofweek/)(DateTime) const | Obtiene el día de la semana para el punto de tiempo especificado. |
| virtual [GetDayOfYear](./getdayofyear/)(DateTime) const | Obtiene el día del año para el punto de tiempo especificado. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtiene el número de días en un mes específico. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtiene el número de días en un mes específico. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Obtiene el número de días en un año específico. |
| virtual [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtiene el número de días en un año específico. |
| virtual [GetEra](./getera/)(DateTime) const | Obtiene la era para el punto de tiempo especificado. |
| virtual [GetHour](./gethour/)(DateTime) const | Obtiene las horas del punto de tiempo especificado. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Obtiene el mes intercalado para el año especificado. |
| virtual [GetLeapMonth](./getleapmonth/)(int, int) const | Obtiene el mes intercalado para el año especificado. |
| virtual [GetMilliseconds](./getmilliseconds/)(DateTime) const | Obtiene los milisegundos del punto de tiempo especificado. |
| virtual [GetMinute](./getminute/)(DateTime) const | Obtiene los minutos del punto de tiempo especificado. |
| virtual [GetMonth](./getmonth/)(DateTime) const | Obtiene el mes para el punto de tiempo especificado. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Obtiene el número de meses en el año especificado. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Obtiene el número de meses en el año especificado. |
| virtual [GetSecond](./getsecond/)(DateTime) const | Obtiene los segundos del punto de tiempo especificado. |
| virtual [GetWeekOfYear](./getweekofyear/)(DateTime, CalendarWeekRule, DayOfWeek) const | Obtiene la semana del año del punto de tiempo especificado. |
| virtual [GetYear](./getyear/)(DateTime) const | Obtiene el año para el punto de tiempo especificado. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Comprueba si el día es bisiesto. |
| virtual [IsLeapDay](./isleapday/)(int, int, int, int) const | Comprueba si el día es bisiesto. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Comprueba si el mes es intercalado. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int, int) const | Comprueba si el mes es intercalado. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Comprueba si el año es bisiesto. |
| virtual [IsLeapYear](./isleapyear/)(int, int) const | Comprueba si el año es bisiesto. |
| [IsValidDay](./isvalidday/)(int, int, int, int) const | Verifica los valores de año, mes, día y era. |
| [operator=](./operator=/)(const Calendar\&) |  |
| static [ReadOnly](./readonly/)(const CalendarPtr\&) | Obtiene la versión de solo lectura del calendario. |
| virtual [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Establece el último año que puede representarse con dos dígitos. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Construye el objeto [DateTime](../../system/datetime/) a partir de componentes. |
| virtual [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Construye el objeto [DateTime](../../system/datetime/) a partir de componentes. |
| virtual [ToFourDigitYear](./tofourdigityear/)(int) const | Convierte el año a un año de 4 dígitos usando la propiedad TwoDigitYearMax. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
