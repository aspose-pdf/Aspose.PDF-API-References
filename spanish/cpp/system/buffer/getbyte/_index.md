---
title: "System::Buffer::GetByte method"
linktitle: "GetByte"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Buffer::GetByte method. Interpreta la matriz tipada especificada como una matriz de bytes cruda y recupera el valor del byte en el desplazamiento de byte especificado en C++."
type: docs
weight: 300
url: /es/cpp/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method


Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la matriz |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const SharedPtr\<Array\<T\>\>\& | La matriz objetivo |
| índice | int | Desplazamiento basado en cero del byte a recuperar |

### ReturnValue

El valor del byte en el índice especificado

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method


Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la vista de la matriz |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const System::Details::ArrayView\<T\>\& | La vista de la matriz objetivo |
| índice | int | Desplazamiento basado en cero del byte a recuperar |

### ReturnValue

El valor del byte en el índice especificado

## Ver también

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method


Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la matriz de pila |
| N | El tamaño de la matriz de pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const System::Details::StackArray\<T, N\>\& | La matriz de pila objetivo |
| índice | int | Desplazamiento basado en cero del byte a recuperar |

### ReturnValue

El valor del byte en el índice especificado

## Ver también

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
