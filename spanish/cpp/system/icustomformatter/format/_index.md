---
title: "Método System::ICustomFormatter::Format"
linktitle: "Format"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ICustomFormatter::Format. Devuelve una representación en cadena de un valor representado por el objeto actual usando el formato especificado en C++."
type: docs
weight: 100
url: /es/cpp/system/icustomformatter/format/
---
## ICustomFormatter::Format method


Devuelve una representación en cadena de un valor representado por el objeto actual usando el formato especificado.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formato | System::String | El formato de cadena |
| arg | System::SharedPtr\<System::Object\> | El objeto a formatear |
| formatProvider | System::SharedPtr\<System::IFormatProvider\> | El objeto que proporciona la información de formato |

### ReturnValue

La representación en cadena de **arg** formateada según el formato especificado por **format** y **formatProvider**

## Ver también

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
