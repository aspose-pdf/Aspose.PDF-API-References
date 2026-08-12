---
title: "System::IO::File::AppendAllLines método"
linktitle: "AppendAllLines"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::File::AppendAllLines method. Agrega cadenas de la colección especificada de cadenas al archivo especificado usando la codificación especificada al escribir cada cadena en una nueva línea. Si el archivo especificado no existe, se crea. El archivo se cierra después de escribir todas las cadenas en C++."
type: docs
weight: 100
url: /es/cpp/system.io/file/appendalllines/
---
## File::AppendAllLines method


Añade cadenas de la colección de cadenas especificada al archivo especificado usando la codificación especificada, escribiendo cada cadena en una nueva línea. Si el archivo especificado no existe, se crea. El archivo se cierra después de escribir todas las cadenas.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo al que se deben agregar las cadenas |
| contenido | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | Las cadenas a escribir en el archivo |
| encoding | const EncodingPtr\& | La codificación de caracteres a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
