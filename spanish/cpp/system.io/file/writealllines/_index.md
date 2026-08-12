---
title: "System::IO::File::WriteAllLines método"
linktitle: "WriteAllLines"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::File::WriteAllLines método. Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas del arreglo de cadenas especificado en él, cada cadena en una nueva línea, usando la codificación especificada en C++."
type: docs
weight: 3600
url: /es/cpp/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method


Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas del arreglo de cadenas especificado en él, cada cadena en una nueva línea, usando la codificación especificada.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | El archivo a crear o sobrescribir |
| contenido | const ArrayPtr\<String\>\& | Una matriz de cadenas |
| encoding | const EncodingPtr\& | La codificación de caracteres a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method


Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas de la colección enumerable de cadenas especificada en él, cada cadena en una nueva línea, usando la codificación especificada.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | El archivo a crear o sobrescribir |
| contenido | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | Una colección enumerable de cadenas |
| encoding | const EncodingPtr\& | La codificación de caracteres a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
