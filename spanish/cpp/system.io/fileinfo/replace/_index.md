---
title: "System::IO::FileInfo::Replace método"
linktitle: "Reemplazar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileInfo::Replace método. Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto FileInfo actual y crea una copia de seguridad del archivo reemplazado en C++."
type: docs
weight: 2000
url: /es/cpp/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) method


Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](../) actual y crea una copia de seguridad del archivo reemplazado.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationFileName | const String\& | Un nombre del archivo a reemplazar |
| destinationBackupFileName | const String\& | Un nombre del archivo de copia de seguridad |

### ReturnValue

Un objeto FileInfor que representa el archivo señalado por **destinationFileName**

## Ver también

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Replace(const String\&, const String\&, bool) method


Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](../) actual y crea una copia de seguridad del archivo reemplazado.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationFileName | const String\& | Un nombre del archivo a reemplazar |
| destinationBackupFileName | const String\& | Un nombre del archivo de copia de seguridad |
| ignoreMetadataErrors | bool | Especifica si los errores de fusión del archivo reemplazado al archivo de reemplazo deben ser ignorados (true) o no (false) |

### ReturnValue

Un objeto FileInfor que representa el archivo señalado por **destinationFileName**

## Ver también

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
