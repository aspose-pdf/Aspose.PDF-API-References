---
title: "System::Int16::TryParse método"
linktitle: "TryParse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método TryParse de la clase System::Int16 en C++."
type: docs
weight: 200
url: /es/cpp/system/int16/tryparse/
---
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method


Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente usando la información de formato y el estilo numérico proporcionados.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir. |
| estilos | Globalization::NumberStyles | Una combinación bit a bit de los valores del enum NumberStyles que especifica el estilo permitido de la representación en cadena de un número. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| resultado | int16_t\& | La referencia a una variable entero con signo de 16 bits donde se coloca el resultado de la conversión. |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso.

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, int16_t\&) method


Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir. |
| resultado | int16_t\& | La referencia a una variable entero con signo de 16 bits donde se coloca el resultado de la conversión. |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso.

## Ver también

* Class [String](../../string/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
