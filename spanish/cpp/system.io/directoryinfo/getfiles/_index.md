---
title: "System::IO::DirectoryInfo::GetFiles método"
linktitle: "GetFiles"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::DirectoryInfo::GetFiles método. Devuelve una matriz que contiene punteros compartidos a objetos FileInfo que representan todos los directorios ubicados en el directorio representado por el objeto actual en C++."
type: docs
weight: 1300
url: /es/cpp/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Devuelve una matriz que contiene punteros compartidos a objetos [FileInfo](../../fileinfo/) que representan todos los directorios ubicados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&) method


Busca los archivos que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los archivos a buscar |

### ReturnValue

Una matriz de punteros compartidos a objetos [FileInfo](../../fileinfo/) que representan los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los archivos a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual |

### ReturnValue

Una matriz de punteros compartidos a objetos [FileInfo](../../fileinfo/) que representan los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
