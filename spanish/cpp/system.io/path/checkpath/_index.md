---
title: "System::IO::Path::CheckPath método"
linktitle: "CheckPath"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::Path::CheckPath método. Determina si la ruta especificada es válida al comprobar si contiene caracteres no válidos. Se lanza una excepción si la ruta contiene caracteres no válidos en C++."
type: docs
weight: 200
url: /es/cpp/system.io/path/checkpath/
---
## Path::CheckPath method


Determina si la ruta especificada es válida comprobando si contiene caracteres no válidos. Se lanza una excepción si la ruta contiene caracteres no válidos.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=true)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta a comprobar |
| msg | const String\& | El mensaje a pasar al constructor del objeto de excepción |
| allow_empty | bool | Especifica si una cadena vacía o nula debe considerarse una ruta correcta (true) o no (false); si este parámetro es false y **path** está vacío se lanza una ArgumentException; si este parámetro es false y **path** es nulo se lanza una ArgumentNullException |

## Ver también

* Class [String](../../../system/string/)
* Class [Path](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
