---
title: "Método System::Attribute::GetCustomAttribute"
linktitle: "GetCustomAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Attribute::GetCustomAttribute. Devuelve un atributo personalizado de un tipo especificado aplicado al tipo especificado en C++."
type: docs
weight: 100
url: /es/cpp/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute method


Devuelve un atributo personalizado de un tipo especificado aplicado al tipo especificado.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | const TypeInfo\& | Atributo de tipo que se recupera |
| attributeType | const TypeInfo\& | Tipo del atributo a recuperar |

### ReturnValue

Un atributo recuperado o null si el tipo especificado no tiene un atributo del tipo especificado.

## Ver también

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
