---
title: "System::Runtime::Serialization::SerializationInfo clase"
linktitle: "SerializationInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Runtime::Serialization::SerializationInfo clase. Mantiene un conjunto de campos con nombre que representan el objeto serializado. No implementado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.runtime.serialization/serializationinfo/
---
## SerializationInfo class


Mantiene un conjunto de campos con nombre que representan el objeto serializado. No implementado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class SerializationInfo : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddValue](./addvalue/)(const System::String\&, float) | Inserta un valor float. No implementado. |
| [AddValue](./addvalue/)(const System::String\&, short) | Inserta un valor short. No implementado. |
| [AddValue](./addvalue/)(const System::String\&, bool) | Inserta un valor boolean. No implementado. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Inserta un valor de objeto. No implementado. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Inserta un valor de objeto con tipo especificado. No implementado. |
| [GetValue](./getvalue/)(const System::String\&, const System::TypeInfo\&) | Recupera un valor del almacén [SerializationInfo](./). No implementado. |
| [SerializationInfo](./serializationinfo/)(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) | Información RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
