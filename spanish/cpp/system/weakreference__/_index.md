---
title: "Clase System::WeakReference<>"
linktitle: "WeakReference<>"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::WeakReference<>. Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado en C++."
type: docs
weight: 8100
url: /es/cpp/system/weakreference__/
---
## WeakReference<> class


Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado.

```cpp
class WeakReference<> : public System::WeakReference<System::Object>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsAlive](./get_isalive/)() const | Obtiene una indicación de si el objeto referenciado por el objeto [WeakReference](../weakreference/) actual ha sido eliminado. |
| [get_Target](./get_target/)() const | Obtiene el objeto (el objetivo) referenciado por el objeto [WeakReference](../weakreference/) actual. |
| [set_Target](./set_target/)(const SmartPtr\<Object\>\&) | Establece el objeto (el objetivo) referenciado por el objeto [WeakReference](../weakreference/) actual. |
| [WeakReference](./weakreference/)() | Constructor predeterminado. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructor desde nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&) | Inicializa una nueva instancia de la clase [WeakReference](../weakreference/), referenciando el objeto especificado. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&, bool) | Inicializa una nueva instancia de la clase [WeakReference](../weakreference/), referenciando el objeto especificado. |
## Ver también

* Class [WeakReference](../weakreference/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
