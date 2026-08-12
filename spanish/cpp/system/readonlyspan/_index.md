---
title: "Clase System::ReadOnlySpan"
linktitle: "ReadOnlySpan"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ReadOnlySpan. Destinado a usarse dentro de la clase Span en C++."
type: docs
weight: 5600
url: /es/cpp/system/readonlyspan/
---
## ReadOnlySpan class


Destinado a usarse dentro de la clase [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span. Esta clase proporciona una forma segura de tipos para trabajar con secuencias contiguas de objetos en modo de solo lectura. Puede usarse para envolver matrices, matrices de pila o punteros sin procesar mientras mantiene la verificación de límites. El [ReadOnlySpan](./) no posee la memoria a la que apunta; solo es una vista de la memoria existente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const Span\<T\>\&) | Construye un span de solo lectura a partir de un span regular. |
| static [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Convierte una matriz a un [ReadOnlySpan](./). |
## Observaciones


Representa una región contigua de solo lectura de memoria arbitraria.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
