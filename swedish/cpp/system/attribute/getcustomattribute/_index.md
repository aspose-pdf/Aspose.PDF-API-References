---
title: "System::Attribute::GetCustomAttribute metod"
linktitle: "GetCustomAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Attribute::GetCustomAttribute metod. Returnerar ett anpassat attribut av en angiven typ som tillämpas på den angivna typen i C++."
type: docs
weight: 100
url: /sv/cpp/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute method


Returnerar ett anpassat attribut av en angiven typ som tillämpas på den angivna typen.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | const TypeInfo\& | Typattribut som hämtas |
| attributeType | const TypeInfo\& | Typ av attributet som ska hämtas |

### ReturnValue

Ett hämtat attribut eller null om den angivna typen inte har ett attribut av den angivna typen.

## Se även

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
