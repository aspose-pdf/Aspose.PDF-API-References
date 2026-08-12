---
title: "Clase System::Nullable"
linktitle: "Nullable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Nullable. Declaración adelantada en C++."
type: docs
weight: 4800
url: /es/cpp/system/nullable/
---
## Nullable class


Declaración adelantada.

```cpp
template<typename T>class Nullable
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de valor subyacente que es extendido por la clase [Nullable](./) |
## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(const T1\&) const | Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](./) especificado. |
| [get_HasValue](./get_hasvalue/)() const | Determina si el objeto actual representa algún valor. |
| [get_Value](./get_value/)() const | Devuelve una copia del valor representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [GetValueOrDefault](./getvalueordefault/)(T) | Devuelve el valor representado por el objeto actual o el valor especificado si el valor representado por el objeto actual es nulo. |
| [GetValueOrDefault](./getvalueordefault/)() |  |
| [IsNull](./isnull/)() const | Determina si el objeto actual representa un valor nulo. |
| [Nullable](./nullable/)() | Construye una instancia que representa un valor nulo. |
| [Nullable](./nullable/)(std::nullptr_t) | Construye una instancia que representa nulo. |
| [Nullable](./nullable/)(const T1\&) | Construye una instancia de la clase [Nullable](./) que representa el valor especificado convertido (si es necesario) al valor del tipo subyacente T. |
| [Nullable](./nullable/)(const Nullable\<T1\>\&) | Construye una instancia que representa un valor que está representado por el objeto [Nullable](./) especificado. El objeto nullable especificado puede representar un valor de tipo diferente al tipo subyacente de la instancia construida, en cuyo caso el valor representado se convierte a un valor de tipo T. |
| [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<bool()>\&, bool) const | Función auxiliar para comprobar si este y **other** no son nulos y llamar a una lambda en ese caso. Usada en implementation.s. |
| [operator const T &](./operatorconstt&/)() const | Devuelve una referencia constante al valor representado por el objeto actual. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual no es nulo. |
| [operator!=](./operator!=/)(const T1\&) const | Determina si el valor representado por el objeto actual no es igual al valor especificado. |
| [operator!=](./operator!=/)(const Nullable\<T1\>\&) const | Determina si el valor representado por el objeto actual no es igual al valor representado por el objeto [Nullable](./) especificado. |
| [operator&=](./operator&=/)(bool) | Aplica [operator&=()](./operator&=/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [operator+](./operator+/)(std::nullptr_t) const | Devuelve una instancia construida por defecto de la clase Nullable<T>. |
| [operator+](./operator+/)(const T1\&) const | Suma valores anulables y no anulables. |
| [operator+](./operator+/)(const Nullable\<T1\>\&) const | Suma valores anulables. |
| [operator+=](./operator+=/)(std::nullptr_t) | Restablece el objeto actual para que represente un valor nulo. |
| [operator+=](./operator+=/)(const T1\&) | Aplica [operator+=()](./operator+=/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [operator+=](./operator+=/)(const Nullable\<T1\>\&) | Aplica [operator+=()](./operator+=/) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](./) especificado como argumento del lado derecho. |
| [operator-](./operator-/)(T1) const | Resta valores anulables y apuntados a nulo. |
| [operator-](./operator-/)(const T1\&) const | Resta valores anulables y no anulables. |
| [operator-](./operator-/)(const Nullable\<T1\>\&) const | Resta valores anulables. |
| [operator-=](./operator-=/)(T1) | Devuelve una instancia de la clase [Nullable](./) que representa un valor nulo. |
| [operator-=](./operator-=/)(const T1\&) | Aplica [operator-=()](./operator-=/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [operator-=](./operator-=/)(const Nullable\<T1\>\&) | Aplica [operator-=()](./operator-=/) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](./) especificado como argumento del lado derecho. |
| [operator<](./operator_/)(std::nullptr_t) const | Siempre devuelve false. |
| [operator<](./operator_/)(const T1\&) const | Determina si el valor representado por el objeto actual es menor que el valor especificado aplicando [operator<()](./operator_/) a estos valores. |
| [operator<](./operator_/)(const Nullable\<T1\>\&) const | Determina si el valor representado por el objeto actual es menor que el valor representado por el objeto [Nullable](./) especificado aplicando [operator<()](./operator_/) a estos valores. |
| [operator<=](./operator_=/)(std::nullptr_t) const | Siempre devuelve false. |
| [operator<=](./operator_=/)(const T1\&) const | Determina si el valor representado por el objeto actual es menor o igual al valor especificado aplicando [operator<=()](./operator_=/) a estos valores. |
| [operator<=](./operator_=/)(const Nullable\<T1\>\&) const | Determina si el valor representado por el objeto actual es menor o igual al valor representado por el objeto [Nullable](./) especificado aplicando [operator<=()](./operator_=/) a estos valores. |
| [operator=](./operator=/)(std::nullptr_t) | Asigna un nulo al objeto actual. |
| [operator=](./operator=/)(const T1\&) | Reemplaza el valor actualmente representado por el objeto con el especificado. |
| [operator=](./operator=/)(const Nullable\<T1\>\&) | Reemplaza el valor actualmente representado por el objeto con el especificado. |
| [operator==](./operator==/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual es nulo. |
| [operator==](./operator==/)(const T1\&) const | Determina si el valor representado por el objeto actual es igual al valor especificado. |
| [operator==](./operator==/)(const Nullable\<T1\>\&) const | Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](./) especificado. |
| [operator>](./operator_/)(std::nullptr_t) const | Siempre devuelve false. |
| [operator>](./operator_/)(const T1\&) const | Determina si el valor representado por el objeto actual es mayor que el valor especificado aplicando [operator>()](./operator_/) a estos valores. |
| [operator>](./operator_/)(const Nullable\<T1\>\&) const | Determina si el valor representado por el objeto actual es mayor que el valor representado por el objeto [Nullable](./) especificado aplicando [operator>()](./operator_/) a estos valores. |
| [operator>=](./operator_=/)(std::nullptr_t) const | Siempre devuelve false. |
| [operator>=](./operator_=/)(const T1\&) const | Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto especificado aplicando [operator>=()](./operator_=/) a estos valores. |
| [operator>=](./operator_=/)(const Nullable\<T1\>\&) const | Determina si el valor representado por el objeto actual es mayor o igual al valor representado por el objeto [Nullable](./) especificado aplicando [operator>=()](./operator_=/) a estos valores. |
| [operator | =](./operator_=/)(bool) | Aplica [operator | =()](./operator_=/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [reset](./reset/)() | Establece el valor representado actualmente a null. |
| [set_Value](./set_value/)(const T\&) | Establece un nuevo valor al objeto nullable. |
| [ToString](./tostring/)() const | Convierte el valor representado por el objeto actual a string. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ValueType](./valuetype/) | Un alias para un tipo del valor representado por esta clase. |
## Observaciones


Representa un valor del tipo especificado que puede asignarse a null. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
