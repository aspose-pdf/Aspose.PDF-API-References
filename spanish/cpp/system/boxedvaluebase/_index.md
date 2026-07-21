---
title: "Clase System::BoxedValueBase"
linktitle: "BoxedValueBase"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::BoxedValueBase. Una clase base que define una interfaz e implementa algunos métodos fundamentales de una clase descendiente que representa un valor empaquetado. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system/boxedvaluebase/
---
## BoxedValueBase class


Una clase base que define una interfaz e implementa algunos métodos fundamentales de una clase descendiente que representa un valor empaquetado. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class BoxedValueBase : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() const | Devuelve el valor que representa el tipo del valor empaquetado representado por el objeto actual. |
| virtual [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | Convierte el valor empaquetado representado por el objeto actual a un entero de 64 bits. |
| virtual [IsBoxedEnum](./isboxedenum/)() | Determina si el objeto actual representa un valor empaquetado de tipo enumeración. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&, bool) | Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado. Un parámetro indica si se debe ignorar mayúsculas y minúsculas al interpretar la cadena que especifica el nombre de la constante de enumeración. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&) | Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado. |
| [ToString](./tostring/)(const System::String\&) const | Convierte el objeto empaquetado a cadena usando la cadena de formato especificada. |
| virtual [ToString](./tostring/)() const | Análogo del método [Object.ToString()](../object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
