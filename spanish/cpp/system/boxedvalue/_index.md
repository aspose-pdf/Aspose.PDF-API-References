---
title: "Clase System::BoxedValue"
linktitle: "BoxedValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::BoxedValue. Representa un valor empaquetado. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system/boxedvalue/
---
## BoxedValue class


Representa un valor empaquetado. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo del valor empaquetado representado por la clase |
## Métodos

| Método | Descripción |
| --- | --- |
| [BoxedValue](./boxedvalue/)(const T\&) | Construye un objeto que representa el valor especificado empaquetado. |
| [Equals](./equals/)(ptr) override | Determina la igualdad de los valores empaquetados representados por el objeto actual y los objetos especificados. |
| [GetHashCode](./gethashcode/)() const override | Devuelve un código hash para el objeto actual. |
| [GetType](./gettype/)() const override | Obtiene el tipo real del objeto. |
| [GetTypeCode](./gettypecode/)() const override | Devuelve el valor que representa el tipo del valor empaquetado representado por el objeto actual. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Devuelve el valor numérico del objeto empaquetado si puede convertirse, cero en caso contrario. |
| [is](./is/)() const | Determina si el tipo del valor empaquetado representado por el objeto actual es **V**. |
| [IsBoxedEnum](./isboxedenum/)() override | Determina si el objeto actual representa un valor empaquetado de tipo enumeración. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&, bool) | Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado. Un parámetro indica si se debe ignorar mayúsculas y minúsculas al interpretar la cadena que especifica el nombre de la constante de enumeración. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&) | Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado. |
| [ToString](./tostring/)() const override | Convierte el valor empaquetado representado por el objeto actual a cadena. |
| [ToString](../boxedvaluebase/tostring/)(const System::String\&) const | Convierte el objeto empaquetado a cadena usando la cadena de formato especificada. |
| [unbox](./unbox/)() const | Desempaqueta el valor representado por el objeto actual. |

## Ver también

* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
