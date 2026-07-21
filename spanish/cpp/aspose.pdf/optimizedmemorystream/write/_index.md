---
title: "Aspose::Pdf::OptimizedMemoryStream::Write método"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::OptimizedMemoryStream::Write método. Cuando se sobrescribe en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf/optimizedmemorystream/write/
---
## OptimizedMemoryStream::Write method


Cuando se sobrescribe en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos.

```cpp
void Aspose::Pdf::OptimizedMemoryStream::Write(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::ArrayPtr\<uint8_t\>\& | Una matriz de bytes. Este método copia *count* bytes de *buffer* al flujo actual. |
| desplazamiento | int32_t | El desplazamiento de bytes basado en cero en *buffer* en el que comenzar a copiar bytes al flujo actual. |
| count | int32_t | El número de bytes que se escribirán en el flujo actual. |
## Observaciones



La suma de *offset* y *count* es mayor que la longitud del búfer.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
