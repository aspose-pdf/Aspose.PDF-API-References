---
title: "System::IO::File::OpenText método"
linktitle: "OpenText"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::File::OpenText método. Abre el archivo existente especificado para leer texto usando codificación UTF-8 sin compartir en C++."
type: docs
weight: 2100
url: /es/cpp/system.io/file/opentext/
---
## File::OpenText method


Abre el archivo existente especificado para leer texto usando la codificación UTF-8 sin compartir.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a abrir |
| encoding | const EncodingPtr\& | La codificación de caracteres a usar |

### ReturnValue

Un puntero compartido a un objeto [StreamWriter](../../streamwriter/) asociado con el archivo abierto

## Ver también

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
