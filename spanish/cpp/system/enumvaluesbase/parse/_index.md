---
title: "System::EnumValuesBase::Parse método"
linktitle: "Analizar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::EnumValuesBase::Parse método. Devuelve un objeto que representa un valor de constante de enumeración del tipo de enumeración especificado con el nombre especificado en C++."
type: docs
weight: 400
url: /es/cpp/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse method


Devuelve un objeto que representa el valor de una constante de enumeración del tipo de enumeración especificado con el nombre especificado.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const TypeInfo\& | El objeto [TypeInfo](../../typeinfo/) que representa el tipo del valor de enumeración a devolver |
| str | const String\& | El nombre de la constante del enum |
| ignoreCase | bool | Especifica si se debe ignorar mayúsculas/minúsculas al interpretar el nombre de la constante del enum |

### ReturnValue

Un objeto que representa el valor de la constante de enumeración cuyo nombre se especifica en **str**.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
