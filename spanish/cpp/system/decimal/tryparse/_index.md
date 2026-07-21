---
title: "Método System::Decimal::TryParse"
linktitle: "TryParse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Decimal::TryParse. Convierte la cadena especificada que contiene la representación en cadena de un número al valor Decimal equivalente en C++."
type: docs
weight: 5800
url: /es/cpp/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) method


Convierte la cadena especificada que contiene la representación en cadena de un número al valor [Decimal](../) equivalente.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir |
| result | Decimal\& | La referencia a una variable [Decimal](../) donde se coloca el resultado de la conversión |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso

## Ver también

* Class [String](../../string/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) method


Convierte la cadena especificada que contiene la representación en cadena de un número al valor [Decimal](../) equivalente usando la información de formato y el estilo numérico proporcionados.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a convertir |
| estilos | Globalization::NumberStyles | Una combinación bit a bit de los valores de la enumeración NumberStyles que especifica el estilo permitido de la representación en cadena de un número |
| proveedor | const SharedPtr\<IFormatProvider\>\& | Un puntero a un objeto que contiene la información de formato de cadena |
| resultado | Decimal\& | Un argumento de salida; contiene el resultado de la conversión |

### ReturnValue

Verdadero si la conversión tuvo éxito, de lo contrario - falso

## Ver también

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
