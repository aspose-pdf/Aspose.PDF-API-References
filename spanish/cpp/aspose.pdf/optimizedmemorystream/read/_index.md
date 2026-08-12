---
title: "Aspose::Pdf::OptimizedMemoryStream::Read método"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::OptimizedMemoryStream::Read método. Cuando se sobrescribe en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream::Read method


Cuando se sobrescribe en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos.

```cpp
int32_t Aspose::Pdf::OptimizedMemoryStream::Read(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::ArrayPtr\<uint8_t\>\& | Una matriz de bytes. Cuando este método devuelve, el búfer contiene la matriz de bytes especificada con los valores |
| desplazamiento | int32_t | El desplazamiento de bytes basado en cero en el que comenzar a almacenar los datos leídos del flujo actual. |
| count | int32_t | El número máximo de bytes que se leerán del flujo actual. |

### ReturnValue

El número total de bytes leídos en el búfer. Esto puede ser menor que el número de bytes solicitados si no hay tantos bytes disponibles actualmente, o cero (0) si se ha alcanzado el final del flujo.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
