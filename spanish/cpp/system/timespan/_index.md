---
title: "Clase System::TimeSpan"
linktitle: "TimeSpan"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::TimeSpan. Representa un intervalo de tiempo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 6400
url: /es/cpp/system/timespan/
---
## TimeSpan class


Representa un intervalo de tiempo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class TimeSpan
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es la suma de los intervalos de tiempo representados por el objeto actual y los objetos especificados. |
| static [Compare](./compare/)(TimeSpan, TimeSpan) | Compara dos objetos [TimeSpan](./). |
| [CompareTo](./compareto/)(TimeSpan) const | Compara el objeto actual y los objetos especificados. |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Compara el objeto actual y los objetos especificados. |
| [Duration](./duration/)() const | Devuelve una nueva instancia del objeto [TimeSpan](./) cuyo valor es el valor absoluto del objeto actual. |
| [Equals](./equals/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual es igual al intervalo de tiempo representado por el objeto especificado. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Determina si el intervalo de tiempo representado por el objeto actual es igual al intervalo de tiempo representado por el objeto especificado. |
| static [Equals](./equals/)(TimeSpan, TimeSpan) | Devuelve true si los objetos especificados representan el mismo intervalo de tiempo, de lo contrario - false. |
| static [FromDays](./fromdays/)(double) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [FromHours](./fromhours/)(double) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [FromMilliseconds](./frommilliseconds/)(double) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [FromMinutes](./fromminutes/)(double) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [FromSeconds](./fromseconds/)(double) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| static [FromTicks](./fromticks/)(int64_t) | Devuelve un nuevo objeto [TimeSpan](./) que representa el intervalo especificado. |
| [get_Days](./get_days/)() const | Devuelve el componente de días del intervalo de tiempo representado por el objeto [TimeSpan](./) actual. |
| [get_Hours](./get_hours/)() const | Devuelve el componente de horas del intervalo de tiempo representado por el objeto [TimeSpan](./) actual. |
| [get_Milliseconds](./get_milliseconds/)() const | Devuelve el componente de milisegundos del intervalo de tiempo representado por el objeto [TimeSpan](./) actual. |
| [get_Minutes](./get_minutes/)() const | Devuelve el componente de minutos del intervalo de tiempo representado por el objeto [TimeSpan](./) actual. |
| [get_Seconds](./get_seconds/)() const | Devuelve el componente de segundos del intervalo de tiempo representado por el objeto [TimeSpan](./) actual. |
| [get_Ticks](./get_ticks/)() const | Devuelve el número de intervalos de 100 nanosegundos que constituyen el intervalo de tiempo representado por el objeto [TimeSpan](./) actual. |
| [get_TotalDays](./get_totaldays/)() const | Devuelve el valor del objeto [TimeSpan](./) actual expresado en días completos y fraccionarios. |
| [get_TotalHours](./get_totalhours/)() const | Devuelve el valor del objeto [TimeSpan](./) actual expresado en horas completas y fraccionarias. |
| [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Devuelve el valor del objeto [TimeSpan](./) actual expresado en milisegundos completos y fraccionarios. |
| [get_TotalMinutes](./get_totalminutes/)() const | Devuelve el valor del objeto [TimeSpan](./) actual expresado en minutos completos y fraccionarios. |
| [get_TotalSeconds](./get_totalseconds/)() const | Devuelve el valor del objeto [TimeSpan](./) actual expresado en segundos completos y fraccionarios. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [IsNull](./isnull/)() const |  |
| [Negate](./negate/)() const | Devuelve una nueva instancia del objeto [TimeSpan](./) que representa el valor negado del objeto [TimeSpan](./) actual. |
| [operator!=](./operator!=/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual no es igual al intervalo de tiempo representado por el objeto especificado. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es la suma de los intervalos de tiempo representados por el objeto actual y los objetos especificados. |
| [operator+](./operator+/)() const | Devuelve a sí mismo. |
| [operator+=](./operator+=/)(TimeSpan) | Asigna al objeto actual el intervalo de tiempo que es la suma del intervalo de tiempo representado por los objetos actual y especificado. |
| [operator-](./operator-/)(TimeSpan) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es el resultado de restar el intervalo de tiempo representado por el objeto especificado del intervalo de tiempo representado por el objeto actual. |
| [operator-](./operator-/)() const | Devuelve una nueva instancia del objeto [TimeSpan](./) que representa el valor negado del objeto [TimeSpan](./) actual. |
| [operator-=](./operator-=/)(TimeSpan) | Asigna al objeto actual el intervalo de tiempo que es el resultado de restar el intervalo de tiempo representado por el objeto especificado del intervalo de tiempo representado por el objeto actual. |
| [operator/](./operator//)(double) const |  |
| [operator/](./operator//)(TimeSpan) const |  |
| [operator/=](./operator/=/)(double) |  |
| [operator<](./operator_/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual es más corto que el intervalo de tiempo representado por el objeto especificado. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual es más corto o igual al intervalo de tiempo representado por el objeto especificado. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const TimeSpan\&) | Establece el intervalo de tiempo representado por el objeto [TimeSpan](./) especificado al objeto [TimeSpan](./) actual. |
| [operator==](./operator==/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual es igual al intervalo de tiempo representado por el objeto especificado. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual es más largo que el intervalo de tiempo representado por el objeto especificado. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(TimeSpan) const | Determina si el intervalo de tiempo representado por el objeto actual es más largo o igual al intervalo de tiempo representado por el objeto especificado. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el proveedor de formato especificado. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando los formatos especificados, el proveedor de formato y los estilos. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Convierte una cadena al objeto [TimeSpan](./) equivalente usando el formato especificado, el proveedor de formato y los estilos. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| [Subtract](./subtract/)(TimeSpan) const | Devuelve una nueva instancia de la clase [TimeSpan](./) que representa un intervalo de tiempo que es el resultado de restar el intervalo de tiempo representado por el objeto especificado del intervalo de tiempo representado por el objeto actual. |
| [TimeSpan](./timespan/)() | Construye un objeto [TimeSpan](./) que representa un intervalo de tiempo cero. |
| explicit [TimeSpan](./timespan/)(int64_t) | Construye una instancia de la clase [TimeSpan](./) que representa el intervalo de tiempo especificado. |
| [TimeSpan](./timespan/)(int, int, int) | Construye una instancia de la clase [TimeSpan](./) que representa el intervalo de tiempo que es igual a la suma del número especificado de horas, minutos y segundos. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Construye una instancia de la clase [TimeSpan](./) que representa el intervalo de tiempo que es igual a la suma del número especificado de horas, minutos, segundos y milisegundos. |
| [TimeSpan](./timespan/)(const TimeSpan\&) | Construye un objeto [TimeSpan](./) que representa el intervalo de tiempo igual al intervalo de tiempo representado por el objeto [TimeSpan](./) especificado. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del intervalo de tiempo representado por el objeto actual. |
| [ToString](./tostring/)(const String\&) const | Convierte el valor del objeto actual a una representación en cadena equivalente, usando el formato especificado. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Convierte el valor del objeto actual a una representación en cadena equivalente, usando el formato y el proveedor de formato especificados. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| static [TryParse](./tryparse/)(const String\&, TimeSpan\&) | Convierte una cadena a un objeto [TimeSpan](./) equivalente y devuelve el resultado de la conversión. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Convierte una cadena a un objeto [TimeSpan](./) equivalente usando el proveedor de formato especificado y devuelve el resultado de la conversión. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Convierte una cadena a un objeto [TimeSpan](./) equivalente usando los formatos y el proveedor de formato especificados, y devuelve el resultado de la conversión. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Convierte una cadena a un objeto [TimeSpan](./) equivalente usando el formato, el proveedor de formato y los estilos especificados, y devuelve el resultado de la conversión. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Convierte una cadena a un objeto [TimeSpan](./) equivalente usando los formatos, el proveedor de formato y los estilos especificados, y devuelve el resultado de la conversión. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Convierte una cadena a un objeto [TimeSpan](./) equivalente usando el formato y el proveedor de formato especificados, y devuelve el resultado de la conversión. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [Type](./type/)() | Devuelve un objeto [TypeInfo](../typeinfo/) que representa la estructura [TimeSpan](./). |
## Campos

| Campo | Descripción |
| --- | --- |
| static [MaxValue](./maxvalue/) | El objeto [TimeSpan](./) que representa el intervalo más largo posible. |
| static [MinValue](./minvalue/) | /// El objeto [TimeSpan](./) que representa el intervalo más corto posible. |
| static constexpr [TicksPerDay](./ticksperday/) | El número de intervalos de 100 nanosegundos en un día (intervalo de 24 horas). |
| static constexpr [TicksPerHour](./ticksperhour/) | El número de intervalos de 100 nanosegundos en una hora. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | El número de intervalos de 100 nanosegundos en un milisegundo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | El número de intervalos de 100 nanosegundos en un minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | El número de intervalos de 100 nanosegundos en un segundo. |
| static [Zero](./zero/) | El objeto [TimeSpan](./) que representa un intervalo cero. |
## Observaciones



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
