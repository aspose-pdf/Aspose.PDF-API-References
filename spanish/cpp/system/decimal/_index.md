---
title: "Clase System::Decimal"
linktitle: "Decimal"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Decimal. Representa un número decimal. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 2000
url: /es/cpp/system/decimal/
---
## Decimal class


Representa un número decimal. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Decimal
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Add](./add/)(const Decimal\&, const Decimal\&) | Suma dos valores [Decimal](./) especificados. |
| static [Ceiling](./ceiling/)(const Decimal\&) | Devuelve el valor entero más pequeño que es mayor o igual al valor especificado. |
| static [Compare](./compare/)(const Decimal\&, const Decimal\&) | Determina si el valor representado por el primer objeto [Decimal](./) es menor, igual o mayor que el valor representado por el segundo objeto [Decimal](./). |
| [CompareTo](./compareto/)(const Decimal\&) const | Determina si el valor representado por el objeto actual es menor, igual o mayor que el valor representado por el objeto especificado. |
| [Decimal](./decimal/)() | Construye una instancia que representa 0. |
| [Decimal](./decimal/)(std::int8_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::int16_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::int32_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::int64_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint8_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint16_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint32_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint64_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(float) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(double) | Construye una instancia que representa el valor especificado. |
| explicit [Decimal](./decimal/)(const std::string\&) | Construye una instancia que representa un valor cuya representación en cadena se especifica como una instancia de la clase std::string. |
| [Decimal](./decimal/)(int32_t, int32_t, int32_t, bool, uint8_t) | Construye un objeto [Decimal](./) a partir de los componentes especificados. |
| [Decimal](./decimal/)(const Decimal\&) | Construye una instancia de la clase [Decimal](./) que representa el mismo número que el objeto [Decimal](./) especificado. |
| [Decimal](./decimal/)(const ArrayPtr\<int32_t\>\&) | Construye una instancia de la clase [Decimal](./) a partir de una matriz de enteros que contiene una representación binaria. |
| [Decimal](./decimal/)(std::nullptr_t) | Siempre lanza ArgumentNullException. |
| [Decimal](./decimal/)(const number_type\&) | Construye una instancia de la clase [Decimal](./) que representa el valor especificado. |
| static [Divide](./divide/)(const Decimal\&, const Decimal\&) | Divide dos valores [Decimal](./) especificados. |
| [Equals](./equals/)(const Decimal\&) const | Determina si los valores representados por el objeto actual y el objeto especificado son iguales. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Determina si los valores representados por el objeto actual y el objeto especificado son iguales. |
| static [Equals](./equals/)(const Decimal\&, const Decimal\&) | Determina si los valores representados por los objetos especificados son iguales. |
| static [Floor](./floor/)(const Decimal\&) | Devuelve el valor entero más grande que es menor o igual al valor especificado. |
| static [FromOACurrency](./fromoacurrency/)(int64_t) | [Convert](../convert/) el valor de moneda OLE especificado al valor [Decimal](./) equivalente. NO IMPLEMENTADO. |
| static [GetBits](./getbits/)(const Decimal\&) | Convierte el objeto [Decimal](./) especificado en la representación binaria del valor que representa. |
| static [GetBytes](./getbytes/)(const Decimal\&, const System::ArrayPtr\<uint8_t\>\&) | [Convert](../convert/) el valor [Decimal](./) especificado a una matriz de bytes. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [GetTypeCode](./gettypecode/)() const | Obtiene el código de tipo del objeto. |
| static [Multiply](./multiply/)(const Decimal\&, const Decimal\&) | Multiplica dos valores [Decimal](./) especificados. |
| static [Negate](./negate/)(const Decimal\&) | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que resulta de la negación del valor representado por el objeto especificado. |
| explicit [operator bool](./operatorbool/)() const | Convierte el valor representado por el objeto actual a un valor booleano. |
| explicit [operator double](./operatordouble/)() const | Convierte el valor representado por el objeto actual a un valor de punto flotante de doble precisión. |
| explicit [operator float](./operatorfloat/)() const | Convierte el valor representado por el objeto actual a un valor de punto flotante de precisión simple. |
| [operator!=](./operator!=/)(const Decimal\&) const | Determina si los valores representados por el objeto actual y el objeto especificado no son iguales. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual es diferente de 0. |
| [operator%](./operator%/)(const Decimal\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de la operación módulo con los valores representados por el objeto actual y el objeto especificado. |
| [operator%=](./operator%=/)(const Decimal\&) | Asigna al objeto actual un nuevo valor que es el resultado de la operación módulo con los valores representados por el objeto actual y el objeto especificado. |
| [operator*](./operator_/)(const Decimal\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de la multiplicación de los valores representados por el objeto actual y los objetos especificados. |
| [operator*=](./operator_=/)(const Decimal\&) | Asigna al objeto actual un nuevo valor que es el resultado de la multiplicación de los valores representados por el objeto actual y los objetos especificados. |
| [operator+](./operator+/)(const Decimal\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es la suma de los valores representados por el objeto actual y los objetos especificados. |
| [operator++](./operator++/)() | Incrementa el valor representado por el objeto actual. |
| [operator+=](./operator+=/)(const Decimal\&) | Asigna al objeto actual un nuevo valor que es la suma de los valores representados por el objeto actual y los objetos especificados. |
| [operator-](./operator-/)(const Decimal\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de la resta del valor representado por el objeto especificado del valor representado por el objeto actual. |
| [operator-](./operator-/)() const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que resulta de la negación del valor representado por el objeto actual. |
| [operator--](./operator--/)() | Decrementa el valor representado por el objeto actual. |
| [operator-=](./operator-=/)(const Decimal\&) | Asigna al objeto actual un nuevo valor que es el resultado de la resta del valor representado por el objeto especificado del valor representado por el objeto actual. |
| [operator/](./operator//)(const Decimal\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de la división del valor representado por el objeto actual entre el valor representado por el objeto especificado. |
| [operator/=](./operator/=/)(const Decimal\&) | Asigna al objeto actual un nuevo valor que es el resultado de la división del valor representado por el objeto actual entre el valor representado por el objeto especificado. |
| [operator<](./operator_/)(const Decimal\&) const | Determina si el valor representado por el objeto actual es menor que el valor representado por el objeto especificado. |
| [operator<=](./operator_=/)(const Decimal\&) const | Determina si el valor representado por el objeto actual es menor o igual que el valor representado por el objeto especificado. |
| [operator=](./operator=/)(const Decimal\&) | Asigna el valor representado por el objeto especificado al objeto actual. |
| [operator==](./operator==/)(const Decimal\&) const | Determina si los valores representados por el objeto actual y el objeto especificado son iguales. |
| [operator==](./operator==/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual es 0. |
| [operator>](./operator_/)(const Decimal\&) const | Determina si el valor representado por el objeto actual es mayor que el valor representado por el objeto especificado. |
| [operator>=](./operator_=/)(const Decimal\&) const | Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto especificado. |
| static [Parse](./parse/)(const String\&) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./). |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./) usando el estilo especificado. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./) usando el proveedor de formato especificado. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./) usando el estilo y el proveedor de formato especificados. |
| static [Remainder](./remainder/)(const Decimal\&, const Decimal\&) | Calcula el resto después de dividir dos valores [Decimal](./). |
| static [Round](./round/)(const Decimal\&, MidpointRounding) | Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de los dos números más cercanos. |
| static [Round](./round/)(const Decimal\&, int, MidpointRounding) | Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de los dos números más cercanos. |
| static [Subtract](./subtract/)(const Decimal\&, const Decimal\&) | Resta un valor [Decimal](./) especificado de otro. |
| static [ToByte](./tobyte/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero sin signo de 8 bits. |
| static [ToDouble](./todouble/)(Decimal) | Convierte el valor [Decimal](./) a un número de punto flotante de doble precisión. |
| static [ToInt16](./toint16/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero con signo de 16 bits. |
| static [ToInt32](./toint32/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero con signo de 32 bits. |
| static [ToInt64](./toint64/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero con signo de 64 bits. |
| static [ToOACurrency](./tooacurrency/)(const Decimal\&) | [Convert](../convert/) el valor [Decimal](./) especificado al valor de moneda OLE equivalente. NO IMPLEMENTADO. |
| static [ToSByte](./tosbyte/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero con signo de 8 bits. |
| static [ToSingle](./tosingle/)(Decimal) | Convierte el valor [Decimal](./) a un número de punto flotante de precisión simple. |
| [ToStdString](./tostdstring/)() const | Devuelve una instancia de std::string que contiene la representación en cadena del valor representado por el objeto. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del valor representado por el objeto. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Convierte el objeto actual a cadena usando la información de formato específica de la cultura. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const Decimal\&, std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Convierte el objeto actual a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToStringInternal](./tostringinternal/)() const | Devuelve la representación en cadena del valor representado por el objeto. Para uso interno. |
| static [ToUInt16](./touint16/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero sin signo de 16 bits. |
| static [ToUInt32](./touint32/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero sin signo de 32 bits. |
| static [ToUInt64](./touint64/)(Decimal) | Convierte el valor [Decimal](./) a un valor entero sin signo de 64 bits. |
| static [Truncate](./truncate/)(const Decimal\&) | Devuelve el objeto [Decimal](./) que representa un valor cuya parte entera es igual a la del valor representado por el objeto [Decimal](./) especificado, con todos los dígitos fraccionarios descartados. |
| static [TryParse](./tryparse/)(const String\&, Decimal\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor [Decimal](./) equivalente. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor [Decimal](./) equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static [Type](./type/)() | Devuelve una referencia al objeto [TypeInfo](../typeinfo/) que representa la información de tipo de la clase [Decimal](./). |
| [~Decimal](./~decimal/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [MaxValue](./maxvalue/) | Representa el número más grande que puede ser representado por la clase [Decimal](./). |
| static [MinusOne](./minusone/) | Representa el número -1. |
| static [MinValue](./minvalue/) | Representa el número más pequeño que puede ser representado por la clase [Decimal](./). |
| static [One](./one/) | Representa el número 1. |
| static [Zero](./zero/) | Representa el número 0. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [number_type](./number_type/) | Un alias para Detail::decimal_number_type. |
## Observaciones



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
This code example produces the following output:
-79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
