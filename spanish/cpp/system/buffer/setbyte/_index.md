---
title: "System::Buffer::SetByte método"
linktitle: "SetByte"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Buffer::SetByte. Interpreta la matriz tipada especificada como una matriz de bytes cruda y establece el valor de byte especificado en el desplazamiento de byte especificado en C++."
type: docs
weight: 400
url: /es/cpp/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method


Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la matriz |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const SharedPtr\<Array\<T\>\>\& | La matriz objetivo |
| índice | int | Desplazamiento basado en cero del byte a establecer |
| valor | uint8_t | El valor del byte a establecer |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method


Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la matriz |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const System::Details::ArrayView\<T\>\& | La vista de la matriz objetivo |
| índice | int | Desplazamiento basado en cero del byte a establecer |
| valor | uint8_t | El valor del byte a establecer |

## Ver también

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method


Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la matriz |
| N | El tamaño de la matriz de pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const System::Details::StackArray\<T, N\>\& | La matriz de pila objetivo |
| índice | int | Desplazamiento basado en cero del byte a establecer |
| valor | uint8_t | El valor del byte a establecer |

## Ver también

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
