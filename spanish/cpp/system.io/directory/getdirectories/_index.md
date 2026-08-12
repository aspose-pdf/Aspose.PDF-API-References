---
title: "Método System::IO::Directory::GetDirectories"
linktitle: "GetDirectories"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::Directory::GetDirectories. Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado en C++."
type: docs
weight: 1000
url: /es/cpp/system.io/directory/getdirectories/
---
## Directory::GetDirectories method


Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | Ruta completa o relativa al directorio en el que buscar |
| searchPattern | const String\& | El patrón de nombre de los directorios a buscar |
| searchOption | SearchOption | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado |

### ReturnValue

Una matriz de rutas completas de los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
