---
title: "Clase System::DateTime"
linktitle: "DateTime"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::DateTime. Representa un valor específico de fecha y hora en el continuo temporal. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 1700
url: /es/cpp/system/datetime/
---
## DateTime class


Representa un valor específico de fecha y hora en el continuo temporal. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class DateTime
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa un valor de fecha y hora que resulta de la adición del intervalo de tiempo especificado al valor de fecha y hora representado por el objeto actual. |
| [AddDays](./adddays/)(double) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de días. |
| [AddHours](./addhours/)(double) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de horas. |
| [AddMilliseconds](./addmilliseconds/)(double) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de milisegundos. |
| [AddMinutes](./addminutes/)(double) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de minutos. |
| [AddMonths](./addmonths/)(int) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de meses. |
| [AddSeconds](./addseconds/)(double) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de segundos. |
| [AddTicks](./addticks/)(int64_t) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el número especificado de intervalos de 100 nanosegundos. |
| [AddYears](./addyears/)(int) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora igual al representado por el objeto actual con el componente de año incrementado en el número especificado. |
| static [Compare](./compare/)(DateTime, DateTime) | Compara dos valores representados por las instancias especificadas de la clase [DateTime](./) y devuelve el valor que indica la posición relativa de los valores en la línea de tiempo. |
| [CompareTo](./compareto/)(DateTime) const | Compara dos valores de fecha y hora representados por el objeto actual y la instancia especificada de la clase [DateTime](./) y devuelve el valor que indica la posición relativa de los valores en la línea de tiempo. |
| [DateTime](./datetime/)() | Construye una instancia que representa el valor de fecha y hora más pequeño posible, igual a MinValue. |
| [DateTime](./datetime/)(int, int, int) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día concretos. |
| [DateTime](./datetime/)(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes y día concretos en el calendario especificado. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo concretos. |
| [DateTime](./datetime/)(int, int, int, int, int, int, DateTimeKind) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo concretos. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto y segundo concretos en el calendario especificado. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, DateTimeKind) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo concretos. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) | Construye una instancia que representa un valor de fecha y hora especificado como un año, mes, día, hora, minuto, segundo y milisegundo concretos en el calendario especificado. |
| [DateTime](./datetime/)(int64_t, DateTimeKind) | Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks. |
| [DateTime](./datetime/)(int64_t, DateTimeKind, bool) | Construye una instancia que representa un valor de fecha y hora especificado como un número de ticks. PARA USO INTERNO. |
| [DateTime](./datetime/)(const DateTime\&) | Construye una instancia mediante copia. |
| static [DaysInMonth](./daysinmonth/)(int, int) | Devuelve el número de días del mes especificado del año especificado. |
| static [Equals](./equals/)(DateTime, DateTime) | Determina si las instancias especificadas de la clase [DateTime](./) representan el mismo valor de fecha y hora. |
| [Equals](./equals/)(DateTime) const | Determina si la instancia especificada de la clase [DateTime](./) representa el mismo valor de fecha y hora que el objeto actual. |
| static [FromBinary](./frombinary/)(int64_t) | Deserializa el valor de fecha y hora desde el entero sin signo de 64 bits especificado y asigna a la nueva instancia de la clase [DateTime](./) ese valor. |
| static [FromFileTime](./fromfiletime/)(int64_t) | Convierte el tiempo de archivo especificado a una instancia de la clase [DateTime](./) que representa el mismo valor de fecha y hora que la hora local. |
| static [FromFileTimeUtc](./fromfiletimeutc/)(int64_t) | Convierte el tiempo de archivo especificado a una instancia de la clase [DateTime](./) que representa el mismo valor de fecha y hora que la hora UTC. |
| static [FromOADate](./fromoadate/)(double) | Devuelve una instancia de la clase [DateTime](./) que representa el valor de fecha y hora equivalente a la OLE Automation Date especificada. |
| static [FromUnixTime](./fromunixtime/)(time_t) | Convierte el valor de tiempo Unix especificado a una instancia de la clase [DateTime](./). USO INTERNO. |
| [get_Date](./get_date/)() const | Devuelve una nueva instancia de la clase [DateTime](./) que representa la parte de fecha de la fecha y hora representada por el objeto actual, con cada componente de la parte de tiempo establecido en 0. |
| [get_Day](./get_day/)() const | Devuelve el número ordinal del día del mes representado por el objeto actual. |
| [get_DayOfWeek](./get_dayofweek/)() const | Devuelve un valor que representa el día de la semana que está representado por el objeto actual. |
| [get_DayOfYear](./get_dayofyear/)() const | Devuelve el número ordinal del día del año representado por el objeto actual. |
| [get_Hour](./get_hour/)() const | Devuelve el componente de hora del valor de fecha y hora representado por el objeto actual. |
| [get_Kind](./get_kind/)() const | Devuelve el valor que indica si la fecha y hora representada por el objeto actual es una fecha y hora local, UTC o ninguna de las dos. |
| [get_Millisecond](./get_millisecond/)() const | Devuelve el componente de milisegundos del valor de fecha y hora representado por el objeto actual. |
| [get_Minute](./get_minute/)() const | Devuelve el componente de minutos del valor de fecha y hora representado por el objeto actual. |
| [get_Month](./get_month/)() const | Devuelve el número ordinal del mes del año representado por el objeto actual. |
| static [get_Now](./get_now/)() | Devuelve una instancia de la clase [DateTime](./) que representa la hora actual como hora local. |
| [get_Second](./get_second/)() const | Devuelve el componente de segundos del valor de fecha y hora representado por el objeto actual. |
| [get_Ticks](./get_ticks/)() const | Devuelve un número de intervalos de 100 nanosegundos transcurridos desde las 0:00:00 UTC, 1 de enero de 0001, en el calendario gregoriano, hasta la fecha y hora representada por el objeto actual. |
| [get_TimeOfDay](./get_timeofday/)() const | Devuelve el valor que representa el intervalo de tiempo desde el comienzo del día representado por el objeto actual hasta el valor de fecha y hora representado por el mismo objeto. |
| static [get_Today](./get_today/)() | Devuelve una instancia de la clase [DateTime](./) que representa la fecha actual con cada componente de la parte de tiempo del valor representado por el objeto establecido en 0. |
| static [get_UtcNow](./get_utcnow/)() | Devuelve una instancia de la clase [DateTime](./) que representa la hora actual como UTC. |
| [get_Year](./get_year/)() const | Devuelve el año representado por el objeto actual. |
| [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Obtiene las partes de la fecha. USO INTERNO. |
| [GetDateTimeFormats](./getdatetimeformats/)() const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateada con uno de los especificadores de formato de fecha y hora estándar. |
| [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateada con el especificador de formato de fecha y hora estándar especificado. |
| [GetDateTimeFormats](./getdatetimeformats/)(const SharedPtr\<IFormatProvider\>\&) const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateada con uno de los especificadores de formato de fecha y hora estándar y con el proveedor de formato especificado. |
| [GetDateTimeFormats](./getdatetimeformats/)(char_t, const SharedPtr\<IFormatProvider\>\&) const | Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateada con el especificador de formato de fecha y hora estándar especificado y el proveedor de formato. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Determina si el valor de fecha y hora representado por el objeto actual se encuentra dentro del rango de horario de verano para la zona horaria actual. |
| static [IsLeapYear](./isleapyear/)(int) | Determina si el año especificado es un año bisiesto. |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(DateTime) const | Determina si el objeto actual y el objeto [DateTime](./) especificado representan valores de fecha y hora distintos. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el intervalo de tiempo especificado. |
| [operator+=](./operator+=/)(TimeSpan) | Establece el objeto actual al valor de fecha y hora que es la suma del valor representado por el objeto actual y el intervalo de tiempo especificado. |
| [operator-](./operator-/)(TimeSpan) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es el resultado de restar el intervalo de tiempo especificado del valor representado por el objeto actual. |
| [operator-](./operator-/)(DateTime) const | Devuelve una instancia de la clase [TimeSpan](../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y el objeto especificado. |
| [operator-=](./operator-=/)(TimeSpan) | Establece el objeto actual al valor de fecha y hora que es el resultado de restar el intervalo de tiempo especificado del valor de fecha y hora representado por el objeto actual. |
| [operator<](./operator_/)(DateTime) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior al valor representado por el objeto [DateTime](./) especificado. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(DateTime) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior o igual al valor representado por el objeto [DateTime](./) especificado. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const DateTime\&) | Asigna el valor representado por la instancia [DateTime](./) especificada al objeto actual. |
| [operator==](./operator==/)(DateTime) const | Determina si el objeto actual y el objeto [DateTime](./) especificado representan el mismo valor de fecha y hora. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(DateTime) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior al valor representado por el objeto [DateTime](./) especificado. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(DateTime) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior o igual al valor representado por el objeto [DateTime](./) especificado. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente utilizando información de formato específica de la cultura. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente utilizando el formato especificado y la información de formato específica de la cultura. El formato de la representación de cadena debe coincidir exactamente con el formato especificado. Lanza una excepción si la conversión falla. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente utilizando los formatos especificados, la información de formato específica de la cultura y el estilo. El formato de la representación de cadena debe coincidir exactamente con uno o más de los formatos especificados. Lanza una excepción si la conversión falla. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [SpecifyKind](./specifykind/)(DateTime, DateTimeKind) | Construye un nuevo objeto [DateTime](./) que representa el mismo número de ticks que el objeto [DateTime](./) especificado y representa hora local, hora UTC o ninguna, según lo especificado por el argumento **kind**. |
| [Subtract](./subtract/)(TimeSpan) const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora que es el resultado de restar el intervalo de tiempo especificado del valor representado por el objeto actual. |
| [Subtract](./subtract/)(DateTime) const | Devuelve una instancia de la clase [TimeSpan](../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por los objetos actual y especificado. |
| [ToBinary](./tobinary/)() const | Serializa el objeto actual. |
| [ToFileTime](./tofiletime/)() const | Devuelve un valor que representa el valor de fecha y hora representado por el objeto actual como tiempo de archivo. |
| [ToFileTimeUtc](./tofiletimeutc/)() const | Convierte el valor de fecha y hora representado por el objeto actual a tiempo de archivo UTC. |
| [ToLocalTime](./tolocaltime/)() const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora representado por el objeto actual como hora local. |
| [ToLongDateString](./tolongdatestring/)() const | Devuelve una cadena que contiene la representación de cadena de fecha larga del objeto actual. |
| [ToLongTimeString](./tolongtimestring/)() const | Devuelve una cadena que contiene la representación de cadena de hora larga del objeto actual. |
| [ToOADate](./tooadate/)() const | Devuelve el valor de fecha y hora representado por el objeto actual como OLE Automation Date. |
| [ToShortDateString](./toshortdatestring/)() const | Devuelve una cadena que contiene la representación de fecha corta del objeto actual. |
| [ToShortTimeString](./toshorttimestring/)() const | Devuelve una cadena que contiene la representación de hora corta del objeto actual. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del valor de fecha y hora representado por el objeto actual usando las convenciones de formato definidas por la cultura actual. |
| [ToString](./tostring/)(const String\&) const | Devuelve una representación en cadena del valor de fecha y hora representado por el objeto actual usando el formato especificado y las convenciones de formato definidas por la cultura actual. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Devuelve una representación en cadena del valor de fecha y hora representado por el objeto actual usando la información de formato especificada. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Devuelve una representación en cadena del valor de fecha y hora representado por el objeto actual usando la información de formato especificada. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToUniversalTime](./touniversaltime/)() const | Devuelve una nueva instancia de la clase [DateTime](./) que representa el valor de fecha y hora representado por el objeto actual como UTC. |
| [ToUnixTime](./tounixtime/)() const | Devuelve un valor que representa el valor de fecha y hora representado por el objeto actual como tiempo Unix. SOLO USO INTERNO. |
| static [TryParse](./tryparse/)(const String\&, DateTime\&) | Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Convierte la representación en cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando la información de formato específica de la cultura y el estilo. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Convierte la representación en cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando el formato especificado, la información de formato específica de la cultura y el estilo. El formato de la representación en cadena debe coincidir exactamente con el formato especificado. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Convierte la representación en cadena especificada de un valor de fecha y hora al objeto [DateTime](./) equivalente usando los formatos especificados, la información de formato específica de la cultura y el estilo. El formato de la representación en cadena debe coincidir exactamente con uno o más de los formatos especificados. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [Type](./type/)() | Devuelve un objeto [TypeInfo](../typeinfo/) que contiene información sobre esta clase. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | El número de intervalos de 100 nanosegundos en el intervalo de tiempo entre el valor [DateTime](./) mínimo posible y el máximo posible. |
| static [MaxValue](./maxvalue/) | Una instancia de la clase [DateTime](./) que representa el valor máximo posible de fecha y hora. |
| static constexpr [MinTicks](./minticks/) | El número mínimo de ticks que una instancia de la clase [DateTime](./) puede representar. |
| static [MinValue](./minvalue/) | Una instancia de la clase [DateTime](./) que representa el valor mínimo posible de fecha y hora. |
| static constexpr [TicksPerDay](./ticksperday/) | El número de ticks en un día. |
| static constexpr [TicksPerHour](./ticksperhour/) | El número de ticks en una hora. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | El número de ticks en un microsegundo. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | El número de ticks en un milisegundo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | El número de ticks en un minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | El número de ticks en un segundo. |
| static [UnixEpoch](./unixepoch/) | Una instancia de la clase [DateTime](./) que representa el inicio de la época Unix (1970.01.01 00:00:00). |
## Observaciones



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Crea la instancia de la clase 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Imprime la instancia en varios formatos.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
This code example produces the following output:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
