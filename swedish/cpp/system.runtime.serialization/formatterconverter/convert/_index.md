---
title: "System::Runtime::Serialization::FormatterConverter::Convert metod"
linktitle: "Konvertera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Runtime::Serialization::FormatterConverter::Convert metod. RTTI-information i C++."
type: docs
weight: 100
url: /sv/cpp/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


RTTI-information.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | System::SharedPtr\<Object\> | Objektet som ska konverteras. |
| type | const TypeInfo\& | Den [System::TypeInfo](../../../system/typeinfo/) som värdet ska konverteras till. |

### ReturnValue

Det konverterade värdet.
## Anmärkningar


Konverterar ett värde till den angivna [System::TypeInfo](../../../system/typeinfo/).
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Konverterar ett värde till den angivna [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | System::SharedPtr\<Object\> | Objektet som ska konverteras. |
| typeCode | TypeCode | Den [System::TypeCode](../../../system/typecode/) som värdet ska konverteras till. |

### ReturnValue

Det konverterade värdet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [TypeCode](../../../system/typecode/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
