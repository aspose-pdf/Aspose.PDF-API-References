---
title: "System::IO::FileMode enum"
linktitle: "FileMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileMode enum. Especifica cómo debe abrirse un archivo en C++."
type: docs
weight: 3100
url: /es/cpp/system.io/filemode/
---
## FileMode enum


Especifica cómo se debe abrir un archivo.

```cpp
enum class FileMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CreateNew | 1 | Crea un archivo nuevo. Si el archivo ya existe, se lanza una excepción. |
| Crear | 2 | Crea un archivo nuevo. Si el archivo ya existe, se sobrescribe. |
| Abrir | 3 | Abre un archivo existente. Si el archivo no existe, se lanza una excepción. |
| OpenOrCreate | 4 | Abre un archivo existente o crea uno nuevo si no existe. |
| Truncar | 5 | Abre un archivo existente y lo trunca para que quede vacío. Si el archivo no existe, se lanza una excepción. |
| Append | 6 | Abra un archivo existente y busque hasta el final o cree uno nuevo si no existe. |

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
