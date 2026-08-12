---
title: "System::IO::FileOptions enumeración"
linktitle: "FileOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileOptions enumeración. Representa opciones avanzadas para crear objetos FileStream en C++."
type: docs
weight: 3200
url: /es/cpp/system.io/fileoptions/
---
## FileOptions enum


Representa opciones avanzadas para crear el objeto [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | No hay opciones adicionales. |
| Encrypted | 16384 | El archivo está cifrado. NO IMPLEMENTADO. |
| DeleteOnClose | 67108864 | El archivo debe eliminarse automáticamente cuando ya no esté en uso. |
| SequentialScan | 134217728 | El archivo debe accederse secuencialmente. |
| RandomAccess | 268435456 | El archivo se accede de forma aleatoria. |
| Asynchronous | 1073741824 | El archivo puede usarse para operaciones de E/S asíncronas. |
| WriteThrough | n/a | Todas las escrituras deben ir directamente al disco, evitando cualquier caché intermedia. |

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
