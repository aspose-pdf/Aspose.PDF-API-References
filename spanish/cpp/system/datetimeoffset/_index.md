---
title: "Clase System::DateTimeOffset"
linktitle: "DateTimeOffset"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::DateTimeOffset. Contiene la fecha y la hora del día relativa al Tiempo Universal Coordinado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1800
url: /es/cpp/system/datetimeoffset/
---
## DateTimeOffset class


Contiene la fecha y la hora del día relativa al Tiempo Universal Coordinado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class DateTimeOffset
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Agrega un intervalo de tiempo especificado al objeto [DateTimeOffset](./). |
| [AddDays](./adddays/)(double) const | Agrega un número especificado de días al objeto [DateTimeOffset](./). |
| [AddHours](./addhours/)(double) const | Agrega un número especificado de horas al objeto [DateTimeOffset](./). |
| [AddMilliseconds](./addmilliseconds/)(double) const | Agrega un número especificado de milisegundos al objeto [DateTimeOffset](./). |
| [AddMinutes](./addminutes/)(double) const | Agrega un número especificado de minutos al objeto [DateTimeOffset](./). |
| [AddMonths](./addmonths/)(int) const | Agrega un número especificado de meses al objeto [DateTimeOffset](./). |
| [AddSeconds](./addseconds/)(double) const | Agrega un número especificado de segundos al objeto [DateTimeOffset](./). |
| [AddTicks](./addticks/)(int64_t) const | Agrega un número especificado de ticks al objeto [DateTimeOffset](./). |
| [AddYears](./addyears/)(int) const | Agrega un número especificado de años al objeto [DateTimeOffset](./). |
| static [Compare](./compare/)(const DateTimeOffset\&, const DateTimeOffset\&) | Compara dos objetos [DateTimeOffset](./). |
| [CompareTo](./compareto/)(const DateTimeOffset\&) const | Compara dos objetos [DateTimeOffset](./). |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Compara dos objetos [DateTimeOffset](./). |
| [DateTimeOffset](./datetimeoffset/)() | Constructor predeterminado. |
| [DateTimeOffset](./datetimeoffset/)(DateTime) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int64_t, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(DateTime, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) | Constructor. |
| static [Equals](./equals/)(const DateTimeOffset\&, const DateTimeOffset\&) | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal. |
| [Equals](./equals/)(const DateTimeOffset\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal. |
| [EqualsExact](./equalsexact/)(const DateTimeOffset\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal y tienen el mismo desplazamiento. |
| [EqualsExact](./equalsexact/)(const SharedPtr\<Object\>\&) const | Comprueba si dos objetos [DateTimeOffset](./) representan el mismo punto temporal y tienen el mismo desplazamiento. |
| static [FromFileTime](./fromfiletime/)(int64_t) | [Convert](../convert/)[Windows](../../system.windows/) tiempo de archivo a fecha y hora con desplazamiento de hora local. |
| static [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(int64_t) | [Convert](../convert/) tiempo Unix a objeto [DateTimeOffset](./). |
| static [FromUnixTimeSeconds](./fromunixtimeseconds/)(int64_t) | [Convert](../convert/) tiempo Unix a objeto [DateTimeOffset](./). |
| [get_Date](./get_date/)() const | Obtiene el componente de fecha del objeto actual. |
| [get_DateTime](./get_datetime/)() const | Obtiene el valor [DateTime](../datetime/). |
| [get_Day](./get_day/)() const | Obtiene el día del mes del objeto actual. |
| [get_DayOfWeek](./get_dayofweek/)() const | Obtiene el día de la semana del objeto actual. |
| [get_DayOfYear](./get_dayofyear/)() const | Obtiene el día del año del objeto actual. |
| [get_Hour](./get_hour/)() const | Obtiene el componente de hora del objeto actual. |
| [get_LocalDateTime](./get_localdatetime/)() const | Obtiene el valor [DateTime](../datetime/) que representa la fecha y hora local. |
| [get_Millisecond](./get_millisecond/)() const | Obtiene el componente de milisegundos del objeto actual. |
| [get_Minute](./get_minute/)() const | Obtiene el componente de minutos del objeto actual. |
| [get_Month](./get_month/)() const | Obtiene el componente de mes del objeto actual. |
| static [get_Now](./get_now/)() | Obtiene [DateTimeOffset](./) cuya fecha y hora se establecen a la hora local actual y cuyo desplazamiento se establece al desplazamiento de la hora local. |
| [get_Offset](./get_offset/)() const | Obtiene el desplazamiento respecto a UTC. |
| [get_Second](./get_second/)() const | Obtiene el componente de segundos del objeto actual. |
| [get_Ticks](./get_ticks/)() const | Obtiene el número de ticks del objeto actual. |
| [get_TimeOfDay](./get_timeofday/)() const | Obtiene la hora del día del objeto actual. |
| [get_UtcDateTime](./get_utcdatetime/)() const | Obtiene el valor [DateTime](../datetime/) que representa la fecha y hora UTC. |
| static [get_UtcNow](./get_utcnow/)() | Obtiene [DateTimeOffset](./) cuya fecha y hora se establecen en la hora UTC actual y cuyo desplazamiento es [TimeSpan::Zero](../timespan/zero/). |
| [get_UtcTicks](./get_utcticks/)() const | Obtiene el número de ticks del objeto actual en tiempo UTC. |
| [get_Year](./get_year/)() const | Obtiene el componente de año del objeto actual. |
| [GetHashCode](./gethashcode/)() const | Obtiene el código hash para el objeto [DateTimeOffset](./) actual. |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(const DateTimeOffset\&) const | Determina si el objeto actual y el objeto [DateTimeOffset](./) especificado representan valores de fecha y hora distintos. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Devuelve una nueva instancia de la clase [DateTimeOffset](./) que representa el valor de fecha y hora que es la suma del valor representado por el objeto actual y el intervalo de tiempo especificado. |
| [operator-](./operator-/)(TimeSpan) const | Devuelve una nueva instancia de la clase [DateTimeOffset](./) que representa el valor de fecha y hora que es el resultado de restar el intervalo de tiempo especificado del valor representado por el objeto actual. |
| [operator-](./operator-/)(const DateTimeOffset\&) const | Devuelve una instancia de la clase [TimeSpan](../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y el objeto especificado. |
| [operator<](./operator_/)(const DateTimeOffset\&) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior al valor representado por el objeto [DateTimeOffset](./) especificado. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(const DateTimeOffset\&) const | Determina si el objeto actual representa el valor de fecha y hora que es anterior o igual al valor representado por el objeto [DateTimeOffset](./) especificado. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator==](./operator==/)(const DateTimeOffset\&) const | Determina si el objeto actual y el objeto [DateTimeOffset](./) especificado representan el mismo valor de fecha y hora. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(const DateTimeOffset\&) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior al valor representado por el objeto [DateTimeOffset](./) especificado. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(const DateTimeOffset\&) const | Determina si el objeto actual representa el valor de fecha y hora que es posterior o igual al valor representado por el objeto [DateTimeOffset](./) especificado. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Convierte la cadena especificada a su equivalente [DateTimeOffset](./). |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Convierte la cadena especificada a un objeto [DateTimeOffset](./) usando el proveedor de formato y el estilo de formato especificados. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Convierte la cadena especificada a un objeto [DateTimeOffset](./) usando el formato, el proveedor de formato y el estilo de formato especificados. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Convierte la cadena especificada a un objeto [DateTimeOffset](./) usando los formatos especificados, el proveedor de formato y el estilo de formato. |
| [Subtract](./subtract/)(TimeSpan) const | Resta un intervalo de tiempo especificado del objeto actual. |
| [Subtract](./subtract/)(const DateTimeOffset\&) const | Resta un valor [DateTimeOffset](./) especificado del objeto actual. |
| [ToFileTime](./tofiletime/)() const | Convierte el objeto actual al tiempo de archivo [Windows](../../system.windows/). |
| [ToLocalTime](./tolocaltime/)() const | Convierte el objeto actual a un objeto que representa la hora local,. |
| [ToOffset](./tooffset/)(TimeSpan) const | Reemplaza el desplazamiento del objeto actual por el desplazamiento especificado. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Convierte el objeto actual a cadena usando el formato especificado y el proveedor de formato. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Convierte el objeto actual a cadena usando el proveedor de formato especificado. |
| [ToString](./tostring/)(const String\&) const | Convierte el objeto actual a cadena usando el formato especificado. |
| [ToString](./tostring/)() const | Convierte el objeto actual a cadena. |
| [ToUniversalTime](./touniversaltime/)() const | Convierte el objeto actual a un objeto que representa la hora UTC,. |
| [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Obtiene los milisegundos transcurridos desde el inicio de la época Unix. |
| [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Obtiene los segundos transcurridos desde el inicio de la época Unix. |
| static [TryParse](./tryparse/)(const String\&, DateTimeOffset\&) | Intenta convertir la cadena especificada a un objeto [DateTimeOffset](./). |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Intenta convertir la cadena especificada a un objeto [DateTimeOffset](./) usando el proveedor de formato y el estilo de formato especificados. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Intenta convertir la cadena especificada a un objeto [DateTimeOffset](./) usando los formatos, el proveedor de formato y el estilo de formato especificados. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Intenta convertir la cadena especificada a un objeto [DateTimeOffset](./) usando el formato, el proveedor de formato y el estilo de formato especificados. |
| static [Type](./type/)() | Devuelve un objeto [TypeInfo](../typeinfo/) que representa la estructura [TimeSpan](../timespan/). |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Obtiene el desplazamiento máximo en ticks. |
| static [MaxValue](./maxvalue/) | Obtiene el mayor valor [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Obtiene el desplazamiento mínimo en ticks. |
| static [MinValue](./minvalue/) | Obtiene el valor más temprano [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | Obtiene el inicio de la época Unix. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
