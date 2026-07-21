---
title: "System::IO::DirectoryInfo::EnumerateDirectories método"
linktitle: "EnumerateDirectories"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::DirectoryInfo::EnumerateDirectories método. Devuelve una colección enumerable que contiene todos los directorios ubicados en el directorio representado por el objeto actual en C++."
type: docs
weight: 500
url: /es/cpp/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() method


Devuelve una colección enumerable que contiene todos los directorios ubicados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&) method


Busca los directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los directorios a buscar |

### ReturnValue

La colección enumerable de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) method


Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los directorios a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual |

### ReturnValue

La colección enumerable de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
