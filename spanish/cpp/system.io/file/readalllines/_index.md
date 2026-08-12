---
title: "System::IO::File::ReadAllLines método"
linktitle: "ReadAllLines"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::File::ReadAllLines método. Lee el contenido del archivo de texto especificado línea por línea a una matriz de cadenas usando la codificación de caracteres especificada en C++."
type: docs
weight: 2400
url: /es/cpp/system.io/file/readalllines/
---
## File::ReadAllLines method


Lee el contenido del archivo de texto especificado línea por línea a una matriz de cadenas usando la codificación de caracteres especificada.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a leer |
| encoding | const EncodingPtr\& | La codificación de caracteres a usar |

### ReturnValue

Una matriz de cadenas, cada elemento de la cual representa una sola línea del archivo especificado

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
