---
title: "Método System::IO::DirectoryInfo::GetDirectories"
linktitle: "GetDirectories"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::DirectoryInfo::GetDirectories. Devuelve una matriz que contiene punteros compartidos a objetos DirectoryInfo que representan todos los directorios ubicados en el directorio representado por el objeto actual en C++."
type: docs
weight: 1200
url: /es/cpp/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() method


Devuelve una matriz que contiene punteros compartidos a objetos [DirectoryInfo](../) que representan todos los directorios ubicados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetDirectories(const String\&) method


Busca los directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los directorios a buscar |

### ReturnValue

Una matriz de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetDirectories(const String\&, SearchOption) method


Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const String\& | El patrón de nombre de los directorios a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual |

### ReturnValue

Una matriz de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
