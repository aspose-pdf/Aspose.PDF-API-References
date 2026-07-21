---
title: "Clase System::Net::PathList"
linktitle: "PathList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::PathList. Representa la lista de instancias de la clase CookieCollection. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 3000
url: /es/cpp/system.net/pathlist/
---
## PathList class


Representa la lista de instancias de la clase [CookieCollection](../cookiecollection/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class PathList : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)() | Crea una nueva instancia. |
| [get_Count](./get_count/)() const | Devuelve el número de elementos. |
| [get_SyncRoot](./get_syncroot/)() const | Devuelve el objeto a través del cual se sincroniza la colección. |
| [GetCookiesCount](./getcookiescount/)() | Devuelve el número de cookies de todos los elementos de la colección. |
| [GetEnumerator](./getenumerator/)() | Devuelve el enumerador de la colección actual. |
| [idx_get](./idx_get/)(String) | Obtiene la colección de cookies mediante la ruta especificada. |
| [idx_set](./idx_set/)(String, System::SharedPtr\<CookieCollection\>) | Establece la colección de cookies mediante la ruta especificada. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
