---
title: "System::ObjectExt clase"
linktitle: "ObjectExt"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ObjectExt. Proporciona métodos estáticos que emulan los métodos de C# Object llamados para tipos C++ que no son Object (cadenas, números, etc.). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio en C++."
type: docs
weight: 5100
url: /es/cpp/system/objectext/
---
## ObjectExt class


Proporciona métodos estáticos que emulan los métodos de C# [Object](../object/) llamados para tipos C++ que no son Object (cadenas, números, etc.). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class ObjectExt : public System::ObjectType
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Convierte valores fundamentales de matrices (que C# hace implícitamente pero C++ aparentemente no lo hace). |
| static [Box](./box/)(const T\&) | Encapsula tipos de valor para convertir a [Object](../object/). Implementación para tipos enum. |
| static [Box](./box/)(const T\&) | Encapsula tipos de valor para convertir a [Object](../object/). Implementación para tipos que no son enum. |
| static [Box](./box/)(const T\&) | Encapsula tipos [Nullable](../nullable/) para convertir a [Object](../object/). |
| static [Box](./box/)(const String\&) | Encapsula valores de cadena. |
| static [BoxEnum](./boxenum/)(T) | Encapsula tipos enum para ser propagados como [Object](../object/). |
| static [CastToIList](./casttoilist/)(const SmartPtr\<Object\>\&) |  |
| static [Coalesce](./coalesce/)(T0, T1) | Implementación de la traducción del operador '??' para tipos no anulables. |
| static [Coalesce](./coalesce/)(System::Nullable\<T0\>, T1) | Implementación de la traducción del operador '??' para tipos anulables. |
| static [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementación de la traducción del operador '??='. |
| static [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementación de la traducción del operador '??' para tipos no anulables. Sobrecarga para el caso en que RT2 sea convertible a RT1. |
| static [Equals](./equals/)(const T\&, const T2\&) |  |
| static [Equals](./equals/)(const T\&, const T2\&) | Sustitución para llamadas de C# [Object.Equals](../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos de puntero inteligente. |
| static [Equals](./equals/)(T, const T2\&) | Sustitución para llamadas de C# [Object.Equals](../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos de estructura. |
| static [Equals](./equals/)(const T\&, const T2\&) | Sustitución para llamadas de C# [Object.Equals](../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos escalares. |
| static [Equals](./equals/)(const char_t(&), String) | Sustitución para llamadas de C# [Object.Equals](../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para literal de cadena con comparación de cadenas. |
| static [Equals](./equals/)(const float\&, const float\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static [Equals](./equals/)(const double\&, const double\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [GetHashCode](./gethashcode/)(const T\&) | Implementa llamadas a [GetHashCode()](./gethashcode/); funciona tanto en subclases de [Object](../object/) como en tipos no relacionados. |
| static [Is](./is/)(const T\&) | Implementa la traducción del operador 'is'. Especialización para tipos empaquetables (valor) que son exactamente eso. |
| static [Is](./is/)(const U\&) | Implementa la traducción del operador 'is'. Especialización para tipos puntero optimizados para clases 'final'. |
| static [Is](./is/)(const U\&) | Implementa la traducción del operador 'is'. Especialización para tipos puntero. |
| static [Is](./is/)(const Object\&) | Implementa la traducción del operador 'is'. Especialización para tipos de valor. |
| static [Is](./is/)(const Object\&) | Implementa la traducción del operador 'is'. Especialización para tipos no convertibles. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos puntero. |
| static [Is](./is/)(const ExceptionWrapper\<U\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos envoltorio de excepción. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos anulables. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos empaquetables con el operador == definido. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos empaquetables sin == definido. |
| static [Is](./is/)(const SmartPtr\<V\>\&) | Implementa la traducción del operador 'is'. Especialización de tipos de valor empaquetados a interfaces. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos enum. |
| static [Is](./is/)(const WeakPtr\<U\>\&) | Implementa la traducción del operador 'is'. Especialización para tipos enum frente a punteros débiles. |
| static [Is](./is/)(const Nullable\<U\>\&) | Implementa la traducción del operador 'is'. Especialización para el tipo [Nullable](../nullable/). |
| static [Is](./is/)(const char16_t *) | Implementa la traducción del operador 'is'. Especialización para literal de cadena. |
| static [Is](./is/)(int32_t) | Implementa la traducción del operador 'is'. Especialización para literal entero. |
| static [IsBoxedValue](./isboxedvalue/)(const SmartPtr\<Object\>\&) | Comprueba si el objeto es un valor empaquetado. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Convierte [Object](../object/) a tipo desconocido, manejando tanto tipos de puntero inteligente como situaciones de valor empaquetado. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Convierte [Object](../object/) a tipo desconocido, manejando tanto tipos de puntero inteligente como situaciones de valor empaquetado. |
| static [ToString](./tostring/)(const char_t *) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(const Nullable\<T\>\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(const T\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(const T\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(T\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(T\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(T\&&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(T\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(const T\&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [ToString](./tostring/)(T\&&) | Sustitución del método ToString de C# para funcionar con cualquier tipo C++. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Desempaqueta tipos de valor después de convertir a [Object](../object/). Implementación para tipos enum. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Desempaqueta tipos de valor después de convertir a [Object](../object/). Implementación para tipos que no son enum ni nullable. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Desempaqueta tipos de valor después de convertir a [Object](../object/). Implementación para tipos que no son enum ni nullable. |
| static [Unbox](./unbox/)(E) | Desempaqueta tipos enum a entero. |
| static [Unbox](./unbox/)(E) | Convierte tipos enum. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Desempaqueta valores de cadena. |
| static [UnboxStringSafe](./unboxstringsafe/)(const SmartPtr\<Object\>\&) | Desempaqueta cadena de un valor empaquetado. |
| static [UnboxToNullable](./unboxtonullable/)(const SmartPtr\<Object\>\&, bool) | Desempaqueta objeto a tipo nullable. |
| static [UnknownIsNull](./unknownisnull/)(T) | Comprueba si el objeto de tipo desconocido es nullptr. Sobrecarga para tipos no escalares. |
| static [UnknownIsNull](./unknownisnull/)(T) | Comprueba si el objeto de tipo desconocido es nullptr. Sobrecarga para tipos escalares. |
| static [UnknownToObject](./unknowntoobject/)(T) | Convierte tipo desconocido a [Object](../object/), manejando tanto tipos de puntero inteligente como situaciones de tipo valor. |
| static [UnknownToObject](./unknowntoobject/)(const T\&) | Convierte tipo desconocido a [Object](../object/), manejando tanto tipos de puntero inteligente como situaciones de tipo valor. |
## Ver también

* Class [ObjectType](../objecttype/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
