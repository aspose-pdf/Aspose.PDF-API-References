---
title: "Método System::DateTimeOffset::TryParseExact"
linktitle: "TryParseExact"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::DateTimeOffset::TryParseExact. Intenta convertir la cadena especificada a un objeto DateTimeOffset usando los formatos especificados, el proveedor de formato y el estilo de formato en C++."
type: docs
weight: 5800
url: /es/cpp/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Intenta convertir la cadena especificada a un objeto [DateTimeOffset](../) usando los formatos especificados, el proveedor de formato y el estilo de formato.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | [String](../../string/) para convertir. |
| formatos | const ArrayPtr\<String\>\& | Arreglos de cadenas de formato. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato. |
| estilos | Globalization::DateTimeStyles | Estilos de formato de fecha y hora. |
| result | DateTimeOffset\& | [DateTimeOffset](../) que es equivalente a la **input**. |

### ReturnValue

true si la **input** se convirtió correctamente, de lo contrario - false.

## Ver también

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Intenta convertir la cadena especificada a un objeto [DateTimeOffset](../) usando el formato especificado, el proveedor de formato y el estilo de formato.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | [String](../../string/) para convertir. |
| formato | const String\& | Cadena de formato. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato. |
| estilos | Globalization::DateTimeStyles | Estilos de formato de fecha y hora. |
| result | DateTimeOffset\& | [DateTimeOffset](../) que es equivalente a la **input**. |

### ReturnValue

true si la **input** se convirtió correctamente, de lo contrario - false.

## Ver también

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
