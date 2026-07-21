---
title: "System::Collections::IEnumeratorImplRefType class"
linktitle: "IEnumeratorImplRefType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::IEnumeratorImplRefType class. Wrapper que crea una implementación no genérica de IEnumerator sobre el iterador genérico IEnumeratorImplRefType - wrapper para los tipos de referencia en C++."
type: docs
weight: 700
url: /es/cpp/system.collections/ienumeratorimplreftype/
---
## IEnumeratorImplRefType class


Wrapper que crea una implementación no genérica de [IEnumerator](../ienumerator/) sobre el iterador genérico [IEnumeratorImplRefType](./) - wrapper para los tipos de referencia.

```cpp
template<typename T>class IEnumeratorImplRefType : public System::Collections::IEnumerator
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Current](./get_current/)() const override | Obtiene el elemento actual. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<System::SharedPtr\<T\>\>\>) | constructor del wrapper |
| [MoveNext](./movenext/)() override | Mueve el enumerador al siguiente elemento. Si no se había referenciado ningún elemento antes, establece la referencia al primer elemento disponible. Si se alcanza el final del contenedor, no hace nada. |

## Ver también

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
