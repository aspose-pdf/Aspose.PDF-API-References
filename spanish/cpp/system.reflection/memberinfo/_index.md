---
title: "Clase System::Reflection::MemberInfo"
linktitle: "MemberInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Reflection::MemberInfo. Proporciona información de reflexión sobre los miembros. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.reflection/memberinfo/
---
## MemberInfo class


Proporciona información de reflexión sobre los miembros. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class MemberInfo : public System::Object
```

## Nested classes

* Class [TypeInternal](./typeinternal/)
## Métodos

| Método | Descripción |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Agrega un atributo a la colección. |
| [get_DeclaringType](./get_declaringtype/)() const | Obtiene el tipo declarador. |
| [get_FullName](./get_fullname/)() const | Obtiene el nombre completo del miembro. Puede ser diferente en partes implementadas manualmente. |
| virtual [get_MemberType](./get_membertype/)() const | Obtiene un valor [System::Reflection::MemberTypes](../membertypes/) que indica el tipo del miembro: método, constructor, evento, etc. |
| [get_Name](./get_name/)() const | Obtiene el nombre del miembro. |
| [get_ReflectedType](./get_reflectedtype/)() const | Obtiene el tipo reflejado. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual. |
| [GetCustomAttributes](./getcustomattributes/)(bool) const | Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ObjectPtr](./objectptr/) | Alias de un puntero compartido a [Object](../../system/object/). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
