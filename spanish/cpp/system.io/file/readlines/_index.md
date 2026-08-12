---
title: "System::IO::File::ReadLines método"
linktitle: "ReadLines"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::File::ReadLines método. Lee el contenido del archivo de texto especificado línea por línea usando la codificación de caracteres especificada y devuelve una colección enumerable de cadenas, cada una de las cuales representa una sola línea del contenido del archivo en C++."
type: docs
weight: 2600
url: /es/cpp/system.io/file/readlines/
---
## File::ReadLines method


Lee el contenido del archivo de texto especificado línea por línea usando la codificación de caracteres especificada y devuelve una colección enumerable de cadenas, cada una de las cuales representa una sola línea del contenido del archivo.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a leer |
| encoding | const EncodingPtr\& | La codificación de caracteres a usar |

### ReturnValue

Una colección enumerable de cadenas que representa el contenido del archivo especificado

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
