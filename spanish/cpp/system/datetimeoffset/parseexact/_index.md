---
title: "Método System::DateTimeOffset::ParseExact"
linktitle: "ParseExact"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::DateTimeOffset::ParseExact. Convierte la cadena especificada a un objeto DateTimeOffset usando los formatos especificados, el proveedor de formato y el estilo de formato en C++."
type: docs
weight: 5600
url: /es/cpp/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Convierte la cadena especificada a un objeto [DateTimeOffset](../) usando los formatos especificados, el proveedor de formato y el estilo de formato.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | [String](../../string/) para convertir. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) de cadenas de formato. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato. |
| estilos | Globalization::DateTimeStyles | Estilos de formato de fecha y hora. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## Ver también

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Convierte la cadena especificada a un objeto [DateTimeOffset](../) usando el formato especificado, el proveedor de formato y el estilo de formato.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | [String](../../string/) para convertir. |
| formato | const String\& | Cadena de formato. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato. |
| estilos | Globalization::DateTimeStyles | Estilos de formato de fecha y hora. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## Ver también

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
