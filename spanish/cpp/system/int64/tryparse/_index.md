---
title: "Método System::Int64::TryParse"
linktitle: "TryParse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método TryParse de la clase System::Int64 en C++."
type: docs
weight: 200
url: /es/cpp/system/int64/tryparse/
---
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method


Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente usando la información de formato proporcionada y el estilo numérico.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir. |
| estilos | Globalization::NumberStyles | Una combinación bit a bit de los valores del enum NumberStyles que especifica el estilo permitido de la representación en cadena de un número. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| resultado | int64_t\& | La referencia a una variable entera con signo de 64 bits donde se coloca el resultado de la conversión. |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso.

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, int64_t\&) method


Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir. |
| resultado | int64_t\& | La referencia a una variable entera con signo de 64 bits donde se coloca el resultado de la conversión. |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso.

## Ver también

* Class [String](../../string/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
