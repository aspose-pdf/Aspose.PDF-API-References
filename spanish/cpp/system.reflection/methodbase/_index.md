---
title: "clase System::Reflection::MethodBase"
linktitle: "MethodBase"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Reflection::MethodBase. Información básica sobre el método. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.reflection/methodbase/
---
## MethodBase class


Información básica sobre el método. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class MethodBase : public System::Reflection::MemberInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Indica el tipo del miembro: método, constructor, evento, etc. |
| static [GetCurrentMethod](./getcurrentmethod/)(const String\&) | Este método permite obtener el nombre del método actual. El traductor sustituye ASPOSE_CURRENT_FUNCTION como parámetro automáticamente. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(MethodBase, CODEPORTING_ARGS(const String\&full_name), CODEPORTING_ARGS(full_name)) |  |
| [MethodBase](./methodbase/)() | Inicializa una nueva instancia de la clase [MethodBase](./). |
## Ver también

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
