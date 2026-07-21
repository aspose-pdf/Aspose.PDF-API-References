---
title: "System::IO::Directory::GetFiles método"
linktitle: "GetFiles"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::Directory::GetFiles método. Busca los archivos que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado en C++."
type: docs
weight: 1200
url: /es/cpp/system.io/directory/getfiles/
---
## Directory::GetFiles method


Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | Ruta completa o relativa al directorio en el que buscar |
| searchPattern | const String\& | El patrón de nombre de los archivos a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado |

### ReturnValue

Una matriz de rutas completas de los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
