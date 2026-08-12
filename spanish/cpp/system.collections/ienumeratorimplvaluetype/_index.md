---
title: "Clase System::Collections::IEnumeratorImplValueType"
linktitle: "IEnumeratorImplValueType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::IEnumeratorImplValueType. Wrapper que crea una implementación no genérica de IEnumerator sobre el iterador genérico IEnumeratorImplRefType - envoltorio para los tipos de valor en C++."
type: docs
weight: 800
url: /es/cpp/system.collections/ienumeratorimplvaluetype/
---
## IEnumeratorImplValueType class


Wrapper que crea una implementación no genérica de [IEnumerator](../ienumerator/) sobre el iterador genérico [IEnumeratorImplRefType](../ienumeratorimplreftype/) - envoltorio para los tipos de valor.

```cpp
template<typename T>class IEnumeratorImplValueType : public System::Collections::IEnumerator
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Current](./get_current/)() const override | Obtiene el elemento actual. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<T\>\>) | constructor del wrapper |
| [MoveNext](./movenext/)() override | Mueve el enumerador al siguiente elemento. Si no se había referenciado ningún elemento antes, establece la referencia al primer elemento disponible. Si se alcanza el final del contenedor, no hace nada. |

## Ver también

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
