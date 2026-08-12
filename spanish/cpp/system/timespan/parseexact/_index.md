---
title: "System::TimeSpan::ParseExact método"
linktitle: "ParseExact"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método ParseExact de la clase System::TimeSpan en C++."
type: docs
weight: 4300
url: /es/cpp/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method


Convierte una cadena al objeto [TimeSpan](../) equivalente usando los formatos especificados, el proveedor de formato y los estilos.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) de cadenas de formato. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato que suministra información de formato específica de la cultura. |
| estilos | Globalization::TimeSpanStyles | Define los elementos que pueden estar presentes en la cadena de entrada. |

### ReturnValue

Intervalo de tiempo que corresponde a la cadena.

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method


Convierte la cadena en un objeto [TimeSpan](../) equivalente usando el formato especificado, el proveedor de formato y los estilos.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| formato | const String\& | Cadena de formato estándar o personalizada. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Proveedor de formato que suministra información de formato específica de la cultura. |
| estilos | Globalization::TimeSpanStyles | Define los elementos que pueden estar presentes en la cadena de entrada. |

### ReturnValue

Intervalo de tiempo que corresponde a la cadena.

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Ver también

* Class [TimeSpan](../)
* Class [String](../../string/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
