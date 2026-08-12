---
title: "System::Array::ConstrainedCopy método"
linktitle: "ConstrainedCopy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::ConstrainedCopy método. Copia un rango de elementos de un System.Array comenzando en la fuente especificada en C++."
type: docs
weight: 4900
url: /es/cpp/system/array/constrainedcopy/
---
## Array::ConstrainedCopy method


Copia un rango de elementos de un [System.Array](../) comenzando en la fuente especificada.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en el array de origen |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Array de origen |
| srcIndex | int64_t | [Index](../../index/) en el array de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | const ArrayPtr\<DstType\>\& | Arreglo de destino |
| dstIndex | int64_t | [Index](../../index/) en el arreglo de destino para comenzar a insertar los elementos copiados |
| count | int64_t | El número de elementos a copiar |
## Observaciones


¡IMPLEMENTACIÓN TEMPORAL EN BRUTO SIN NINGÚN DESHACIMIENTO!
## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
