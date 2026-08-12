---
title: "System::WeakReference< T > clase"
linktitle: "WeakReference< T >"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::WeakReference< T > class. Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado en C++."
type: docs
weight: 8000
url: /es/cpp/system/weakreference_t_/
---
## WeakReference< T > class


Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de un objeto referenciado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [operator!=](./operator!=/)(std::nullptr_t) const | Comprueba si el objeto referenciado no es nulo. |
| [operator!=](./operator!=/)(const WeakReference\<T\>\&) const | Compara el objeto referenciado con otra instancia de la clase [WeakReference](../weakreference/). |
| [operator==](./operator==/)(std::nullptr_t) const | Comprueba si el objeto referenciado es nulo. |
| [operator==](./operator==/)(const WeakReference\<T\>\&) const | Compara el objeto referenciado con otra instancia de la clase [WeakReference](../weakreference/). |
| [reset](./reset/)() |  |
| [SetTarget](./settarget/)(const SmartPtr\<T\>\&) | Establece el objeto (el objetivo) referenciado por el objeto [WeakReference](../weakreference/) actual. |
| [TryGetTarget](./trygettarget/)(const SmartPtr\<T\>\&) const | Obtiene el objeto (el objetivo) referenciado por el objeto [WeakReference](../weakreference/) actual. |
| [WeakReference](./weakreference/)() | Constructor predeterminado. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructor desde nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&) | Inicializa una nueva instancia de la clase [WeakReference](../weakreference/), referenciando el objeto especificado. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&, bool) | Inicializa una nueva instancia de la clase [WeakReference](../weakreference/), referenciando el objeto especificado. |

## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
