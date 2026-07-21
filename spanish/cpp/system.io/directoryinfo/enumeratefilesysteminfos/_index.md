---
title: "System::IO::DirectoryInfo::EnumerateFileSystemInfos método"
linktitle: "EnumerateFileSystemInfos"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::DirectoryInfo::EnumerateFileSystemInfos método. Devuelve una colección enumerable que contiene todos los archivos y directorios ubicados en el directorio representado por el objeto actual en C++."
type: docs
weight: 700
url: /es/cpp/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Devuelve una colección enumerable que contiene todos los archivos y directorios ubicados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los archivos y directorios a buscar |

### ReturnValue

La colección enumerable de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los archivos y directorios a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual |

### ReturnValue

La colección enumerable de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
