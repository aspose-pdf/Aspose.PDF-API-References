---
title: "System::Byte::TryParse método"
linktitle: "TryParse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método TryParse de la clase System::Byte en C++."
type: docs
weight: 200
url: /es/cpp/system/byte/tryparse/
---
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method


Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente usando la información de formato proporcionada y el estilo numérico.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir. |
| estilos | Globalization::NumberStyles | Una combinación bit a bit de los valores del enum NumberStyles que especifica el estilo permitido de la representación en cadena de un número. |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| resultado | uint8_t\& | La referencia a una variable entera sin signo de 8 bits donde se coloca el resultado de la conversión. |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso.

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, uint8_t\&) method


Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir. |
| resultado | uint8_t\& | La referencia a una variable entera sin signo de 8 bits donde se coloca el resultado de la conversión. |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso.

## Ver también

* Class [String](../../string/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
