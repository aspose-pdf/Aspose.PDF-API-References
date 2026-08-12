---
title: "método Aspose::Pdf::OptimizedMemoryStream::Seek"
linktitle: "Seek"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "método Aspose::Pdf::OptimizedMemoryStream::Seek. Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.pdf/optimizedmemorystream/seek/
---
## OptimizedMemoryStream::Seek method


Cuando se sobrescribe en una clase derivada, establece la posición dentro del flujo actual.

```cpp
int64_t Aspose::Pdf::OptimizedMemoryStream::Seek(int64_t offset, System::IO::SeekOrigin origin) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| desplazamiento | int64_t | Un desplazamiento de bytes relativo al parámetro *origin*. |
| origin | System::IO::SeekOrigin | Un valor de tipo [T:System::IO::SeekOrigin](../) que indica el punto de referencia utilizado para obtener la nueva posición. |

### ReturnValue

La nueva posición dentro del flujo actual.

## Ver también

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
