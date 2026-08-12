---
title: "System::EnumValues::GetValueOf metod"
linktitle: "GetValueOf"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::EnumValues::GetValueOf metod. Returnerar det inneslutna värdet för enum‑konstanten med det angivna namnet i C++."
type: docs
weight: 500
url: /sv/cpp/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method


Returnerar ett inbakat värde för uppräkningskonstanten med det specificerade namnet.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Namnet på enum‑konstanten |
| ignoreCase | bool | Anger om skiftläget ska ignoreras när namnet på enum‑konstanten tolkas |

### ReturnValue

Ett inneslutet värde för enum‑konstanten vars namn anges i **str**.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## EnumValues::GetValueOf(long) const method


Returnerar ett inbakat värde för uppräkningskonstanten med det specificerade värdet.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| val | long | Värdet för enum‑konstanten |

### ReturnValue

Ett inramat värde av enum-konstanten vars värde anges i **str**.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
