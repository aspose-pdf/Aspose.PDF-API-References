---
title: "System::Globalization::DateTimeFormatInfo clase"
linktitle: "DateTimeFormatInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::DateTimeFormatInfo. Conjunto de parámetros de formato de fecha y hora. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Conjunto de parámetros de formato de fecha y hora. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona la información de formato. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Constructor predeterminado, construye información de formato invariante. |
| [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Obtiene los nombres abreviados de los días. |
| [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Obtiene los nombres abreviados de los meses en forma genitiva. |
| [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Obtiene los nombres abreviados de los meses. |
| [get_AMDesignator](./get_amdesignator/)() const | Obtiene el designador AM. |
| [get_Calendar](./get_calendar/)() const | Obtiene el calendario asociado al formateador. |
| [get_CalendarWeekRule](./get_calendarweekrule/)() const | Obtiene la regla de semana del calendario asociada al formateador. |
| static [get_CurrentInfo](./get_currentinfo/)() | Obtiene el formateador de fecha y hora del hilo actual. |
| [get_DateSeparator](./get_dateseparator/)() const | Obtiene el separador de fecha. |
| [get_DayNames](./get_daynames/)() const | Obtiene los nombres de los días. |
| [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Obtiene el primer día de la semana. |
| [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Obtiene el patrón completo de fecha y hora. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Obtiene el formateador invariante de fecha y hora. |
| [get_IsReadOnly](./get_isreadonly/)() const | Comprueba si el formateador es de solo lectura. |
| [get_LongDatePattern](./get_longdatepattern/)() const | Obtiene el patrón de fecha larga. |
| [get_LongTimePattern](./get_longtimepattern/)() const | Obtiene el patrón de hora larga. |
| [get_MonthDayPattern](./get_monthdaypattern/)() const | Obtiene el patrón de día del mes. |
| [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Obtiene los nombres de los meses en forma genitiva. |
| [get_MonthNames](./get_monthnames/)() const | Obtiene los nombres de los meses. |
| [get_NativeCalendarName](./get_nativecalendarname/)() const | Obtiene el nombre del calendario nativo si está disponible. |
| [get_PMDesignator](./get_pmdesignator/)() const | Obtiene el designador PM. |
| [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Obtiene el patrón RFC1123. |
| [get_ShortDatePattern](./get_shortdatepattern/)() const | Obtiene el patrón de fecha corta. |
| [get_ShortestDayNames](./get_shortestdaynames/)() const | Obtiene los nombres de día más cortos posibles. |
| [get_ShortTimePattern](./get_shorttimepattern/)() const | Obtiene el patrón de hora corta. |
| [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Obtiene el patrón de fecha y hora ordenable. |
| [get_TimeSeparator](./get_timeseparator/)() const | Obtiene el separador de hora. |
| [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Obtiene el patrón universal ordenable de fecha y hora. |
| [get_YearMonthPattern](./get_yearmonthpattern/)() const | Obtiene el patrón de año y mes. |
| [GetAbbreviatedDayName](./getabbreviateddayname/)(DayOfWeek) const | Obtiene el nombre abreviado del día de la semana. |
| [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Obtiene el nombre abreviado de la era. |
| [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Obtiene el nombre abreviado del mes. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Obtiene todos los patrones en los que se pueden formatear los valores de fecha y hora. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Obtiene todos los patrones en los que se pueden formatear los valores de fecha y hora usando la cadena de formato especificada. |
| [GetDayName](./getdayname/)(DayOfWeek) const | Obtiene el nombre del día de la semana. |
| [GetEra](./getera/)(const String\&) const | Obtiene la era por nombre. |
| [GetEraName](./geteraname/)(int) const | Obtiene el nombre de la era. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Obtiene el formateador de tipo específico. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Obtiene el formateador asociado con el proveedor de formato. |
| [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Obtiene el nombre del mes de año bisiesto. |
| [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Obtiene el nombre del mes en genitivo. |
| [GetMonthName](./getmonthname/)(int) const | Obtiene el nombre del mes. |
| [GetShortestDayName](./getshortestdayname/)(DayOfWeek) const | Obtiene el nombre más corto del día de la semana especificado. |
| [operator=](./operator=/)(const DateTimeFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(const DateTimeFormatInfoPtr\&) | Obtiene la versión de solo lectura del formateador. |
| [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const ArrayPtr\<String\>\&) | Establece los nombres abreviados de los días. |
| [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const ArrayPtr\<String\>\&) | Establece los nombres abreviados de los meses en forma genitiva. |
| [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const ArrayPtr\<String\>\&) | Establece los nombres abreviados de los meses. |
| [set_AMDesignator](./set_amdesignator/)(const String\&) | Establece el designador AM. |
| [set_Calendar](./set_calendar/)(const SharedPtr\<Calendar\>\&) | Establece el calendario asociado al formateador. |
| [set_CalendarWeekRule](./set_calendarweekrule/)(CalendarWeekRule) | Establece la regla de semana del calendario asociada al formateador. |
| [set_DateSeparator](./set_dateseparator/)(const String\&) | Establece el separador de fecha. |
| [set_DayNames](./set_daynames/)(const ArrayPtr\<String\>\&) | Establece los nombres de los días. |
| [set_FirstDayOfWeek](./set_firstdayofweek/)(DayOfWeek) | Establece el primer día de la semana. |
| [set_FullDateTimePattern](./set_fulldatetimepattern/)(const String\&) | Establece el patrón completo de fecha y hora. |
| [set_LongDatePattern](./set_longdatepattern/)(const String\&) | Establece el patrón de fecha larga. |
| [set_LongTimePattern](./set_longtimepattern/)(const String\&) | Establece el patrón de hora larga. |
| [set_MonthDayPattern](./set_monthdaypattern/)(const String\&) | Establece el patrón de día del mes. |
| [set_MonthGenitiveNames](./set_monthgenitivenames/)(const ArrayPtr\<String\>\&) | Establece los nombres de los meses en forma genitiva. |
| [set_MonthNames](./set_monthnames/)(const ArrayPtr\<String\>\&) | Establece los nombres de los meses. |
| [set_PMDesignator](./set_pmdesignator/)(const String\&) | Establece el designador PM. |
| [set_ShortDatePattern](./set_shortdatepattern/)(const String\&) | Establece el patrón de fecha corta. |
| [set_ShortestDayNames](./set_shortestdaynames/)(const ArrayPtr\<String\>\&) | Establece los nombres de día más cortos posibles. |
| [set_ShortTimePattern](./set_shorttimepattern/)(const String\&) | Establece el patrón de hora corta. |
| [set_TimeSeparator](./set_timeseparator/)(const String\&) | Establece el separador de hora. |
| [set_YearMonthPattern](./set_yearmonthpattern/)(const String\&) | Establece el patrón de año y mes. |
| [SetAllDateTimePatterns](./setalldatetimepatterns/)(const ArrayPtr\<String\>\&, char16_t) | Establece los patrones para el formato especificado. |
## Ver también

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
