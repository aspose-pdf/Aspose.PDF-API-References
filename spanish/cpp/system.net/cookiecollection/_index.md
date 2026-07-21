---
title: "System::Net::CookieCollection clase"
linktitle: "CookieCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::CookieCollection. Representa una lista de cookies ordenadas. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.net/cookiecollection/
---
## CookieCollection class


Representa una lista de cookies ordenadas. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class CookieCollection : public System::Collections::Generic::ICollection<System::SharedPtr<System::Net::Cookie>>
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [Stamp](./stamp/) | Información RTTI. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Cookie\>\&) override | Agrega una cookie a la colección. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Añade cookies de la colección especificada a la actual. |
| [Clear](./clear/)() override | Elimina todas las cookies de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<Cookie\>\&) const override | Comprueba si la colección contiene la cookie especificada. |
| [CookieCollection](./cookiecollection/)() | Construye una nueva instancia. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos en la colección. |
| [get_IsOtherVersionSeen](./get_isotherversionseen/)() | Devuelve un valor que indica si la colección contiene una cookie con una versión que no es igual a [Cookie::MaxSupportedVersion](../cookie/maxsupportedversion/). |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador. |
| [idx_get](./idx_get/)(int32_t) | Devuelve una cookie de la colección de cookies en el índice especificado. |
| [idx_get](./idx_get/)(String) | Devuelve una cookie de la colección de cookies por el nombre especificado. |
| [IndexOf](./indexof/)(System::SharedPtr\<Cookie\>) | Devuelve el índice de la cookie especificada. |
| [InternalAdd](./internaladd/)(System::SharedPtr\<Cookie\>, bool) | Añade la cookie especificada a la colección. |
| [Remove](./remove/)(const System::SharedPtr\<Cookie\>\&) override | Elimina la cookie especificada de la colección. |
| [RemoveAt](./removeat/)(int32_t) | Elimina una cookie en el índice especificado. |
| [TimeStamp](./timestamp/)(CookieCollection::Stamp) | Actualiza la marca de tiempo según el escenario especificado y devuelve un nuevo valor. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
