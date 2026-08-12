---
title: "Clase System::EnumValues"
linktitle: "EnumValues"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::EnumValues. Proporciona información meta sobre las constantes de enumeración del tipo enum **E** en C++."
type: docs
weight: 2400
url: /es/cpp/system/enumvalues/
---
## EnumValues class


Proporciona información meta sobre las constantes de enumeración del tipo enum **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


| Parámetro | Descripción |
| --- | --- |
| E | El tipo de enumeración |
## Métodos

| Método | Descripción |
| --- | --- |
| [EnumValues](./enumvalues/)() | Construye una instancia. |
| [GetNames](./getnames/)() const override | Devuelve una matriz que contiene todos los nombres de la enumeración **E**. |
| static [GetNames](../enumvaluesbase/getnames/)(const TypeInfo\&) | Recupera una matriz con los nombres de las constantes en una enumeración especificada. |
| [GetUnderlyingType](./getunderlyingtype/)() const override | Devuelve el tipo subyacente de la enumeración especificada. |
| static [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const TypeInfo\&) | Devuelve el tipo subyacente de la enumeración especificada. |
| [GetValueOf](./getvalueof/)(const String\&, bool) const override | Devuelve el valor empaquetado de la constante de enumeración con el nombre especificado. |
| [GetValueOf](./getvalueof/)(long) const override | Devuelve el valor empaquetado de la constante de enumeración con el valor especificado. |
| [GetValues](./getvalues/)() const override | Devuelve una matriz que contiene todos los valores de la enumeración **E**. |
| static [GetValues](../enumvaluesbase/getvalues/)(const TypeInfo\&) | Devuelve una matriz que contiene todos los valores del tipo de enumeración especificado. |
| static [Parse](../enumvaluesbase/parse/)(const TypeInfo\&, const String\&, bool) | Devuelve un objeto que representa el valor de una constante de enumeración del tipo de enumeración especificado con el nombre especificado. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, uint64_t) | Convierte el valor entero sin signo de 64 bits especificado a un miembro de enumeración. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Convierte el objeto especificado con un valor entero a un miembro de enumeración. |
| virtual [~EnumValues](./~enumvalues/)() | Destructor. |

## Ver también

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
