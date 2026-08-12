---
title: "System::BoxedEnum class"
linktitle: "BoxedEnum"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::BoxedEnum class. Representa un valor de enumeración empaquetado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system/boxedenum/
---
## BoxedEnum class


Representa un valor de enumeración empaquetado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```


| Parámetro | Descripción |
| --- | --- |
| E | Tipo del valor de enumeración |
| UT | El tipo subyacente de la enumeración **E** |
## Métodos

| Método | Descripción |
| --- | --- |
| [BoxedEnum](./boxedenum/)(E) | Construye una instancia que representa el valor de enumeración especificado. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Convierte el valor de la constante de enumeración empaquetada a un valor entero de 64 bits. |
| [IsBoxedEnum](./isboxedenum/)() override | Determina si el objeto actual representa un valor empaquetado del tipo enum. |
| [ToString](./tostring/)() const override | Convierte el valor empaquetado representado por el objeto actual a cadena. |

## Ver también

* Class [BoxedValue](../boxedvalue/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
