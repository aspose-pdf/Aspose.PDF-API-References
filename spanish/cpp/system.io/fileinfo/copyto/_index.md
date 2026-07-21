---
title: "System::IO::FileInfo::CopyTo método"
linktitle: "CopyTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileInfo::CopyTo método. Copia el archivo representado por el objeto actual a la ubicación especificada. Si el archivo de destino ya existe, la copia falla en C++."
type: docs
weight: 300
url: /es/cpp/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) method


Copia el archivo representado por el objeto actual a la ubicación especificada. Si el archivo de destino ya existe, la copia falla.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destFileName | const String\& | El nombre del archivo de destino |

### ReturnValue

Un objeto [FileInfo](../) que representa la copia

## Ver también

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::CopyTo(const String\&, bool) method


Copia el archivo representado por el objeto actual a la ubicación especificada. Un parámetro indica si el archivo de destino existente debe sobrescribirse.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destFileName | const String\& | El nombre del archivo de destino |
| sobrescribir | bool | Verdadero si el archivo de destino existente debe sobrescribirse, falso si la copia debe fallar si el archivo de destino ya existe |

### ReturnValue

Un objeto [FileInfo](../) que representa la copia

## Ver también

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
