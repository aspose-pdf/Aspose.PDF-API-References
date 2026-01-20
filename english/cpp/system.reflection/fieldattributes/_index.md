---
title: System::Reflection::FieldAttributes enum
linktitle: FieldAttributes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::FieldAttributes enum. Reflected field attributes in C++.'
type: docs
weight: 1200
url: /cpp/system.reflection/fieldattributes/
---
## FieldAttributes enum


Reflected field attributes.

```cpp
enum class FieldAttributes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| FieldAccessMask | 7 | Member access mask. Use this mask to retrieve accessibility information. |
| PrivateScope | 0 | Non-referancable members. |
| Private | 1 | Private members. |
| FamANDAssem | 2 | Private and assembly-scoped members. |
| Assembly | 3 | Assembly-scoped members. |
| Family | 4 | Members accessible by type and subtypes. |
| FamORAssem | 5 | Members accessible by type, sub-types and assembly. |
| Public | 6 | Members accessible by anyone. |
| Static | 16 | Static members as opposite to instance members. |
| InitOnly | 32 | Const members that can only be initialized but not changed. |
| Literal | 64 | Compile time constant members. |
| NotSerialized | 128 | Not serialized members. |
| SpecialName | 512 | Special field of one of the below names. |
| PinvokeImpl | 8192 | Interop forwarded implementation. |
| ReservedMask | 38144 | Reserved flags for runtime use only. |
| RTSpecialName | 1024 | Runtim eshould check name encoding. |
| HasFieldMarshal | 4096 | Marshalling information is present. |
| HasDefault | 32768 | Default value is present. |
| HasFieldRVA | 256 | RVA is present. |

## See Also

* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
