---
title: "System::DateTime::Parse método"
linktitle: "Analizar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::DateTime::Parse método. Convierte la representación de cadena especificada de un valor de fecha y hora al objeto DateTime equivalente en C++."
type: docs
weight: 6600
url: /es/cpp/system/datetime/parse/
---
## DateTime::Parse(const String\&) method


Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La representación de cadena de un valor de fecha y hora a convertir. |

### ReturnValue

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora equivalente al representado por la cadena especificada.

## Ver también

* Class [DateTime](../)
* Class [String](../../string/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Ver también

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Ver también

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente utilizando información de formato específica de la cultura.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La representación de cadena de un valor de fecha y hora a convertir. |
| provider | const SharedPtr\<IFormatProvider\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |
| styles | Globalization::DateTimeStyles | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |

### ReturnValue

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora equivalente al representado por la cadena especificada.

## Ver también

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Ver también

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
