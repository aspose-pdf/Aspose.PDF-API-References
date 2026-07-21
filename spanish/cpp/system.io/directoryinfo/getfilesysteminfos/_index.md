---
title: "System::IO::DirectoryInfo::GetFileSystemInfos método"
linktitle: "GetFileSystemInfos"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::DirectoryInfo::GetFileSystemInfos método. Devuelve una matriz que contiene punteros compartidos a objetos FileSystemInfo que representan todos los archivos y directorios ubicados en el directorio representado por el objeto actual en C++."
type: docs
weight: 1400
url: /es/cpp/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method


Devuelve una matriz que contiene punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan todos los archivos y directorios ubicados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&) method


Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los archivos y directorios a buscar |

### ReturnValue

Una matriz de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method


Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los archivos y directorios a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual |

### ReturnValue

Una matriz de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
