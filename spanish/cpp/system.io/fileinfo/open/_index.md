---
title: "Método System::IO::FileInfo::Open"
linktitle: "Abrir"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::FileInfo::Open. Abre el archivo representado por el objeto actual en el modo especificado para lectura y escritura y sin compartir en C++."
type: docs
weight: 1600
url: /es/cpp/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) method


Abre el archivo representado por el objeto actual en el modo especificado para lectura y escritura y sin compartir.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modo | FileMode | Especifica el modo en el que abrir el archivo |

### ReturnValue

Un objeto [FileStream](../../filestream/) asociado con el archivo representado por el objeto actual

## Ver también

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess) method


Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y sin compartir.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modo | FileMode | Especifica el modo en el que abrir el archivo |
| acceso | FileAccess | El tipo de acceso solicitado |

### ReturnValue

Un objeto [FileStream](../../filestream/) asociado con el archivo representado por el objeto actual

## Ver también

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess, FileShare) method


Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y la opción de compartir.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modo | FileMode | Especifica el modo en el que abrir el archivo |
| acceso | FileAccess | El tipo de acceso solicitado |
| share | FileShare | El tipo de acceso que otros objetos [FileStream](../../filestream/) tienen al archivo abierto |

### ReturnValue

Un objeto [FileStream](../../filestream/) asociado con el archivo representado por el objeto actual

## Ver también

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
