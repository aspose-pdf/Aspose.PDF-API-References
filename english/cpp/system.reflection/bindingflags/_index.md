---
title: System::Reflection::BindingFlags enum
linktitle: BindingFlags
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::BindingFlags enum. Degines members and types lookup modes and bindings in C++.'
type: docs
weight: 1100
url: /cpp/system.reflection/bindingflags/
---
## BindingFlags enum


Degines members and types lookup modes and bindings.

```cpp
enum class BindingFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | No special options. |
| IgnoreCase | 1 | Ignore case of name when looking for item. |
| DeclaredOnly | 2 | Only look for members declared in type and not in basetypes. |
| Instance | 4 | Look through instance members. |
| Static | 8 | Look through static members. |
| Public | 16 | Look through public members. |
| NonPublic | 32 | Look through non-public members. |
| FlattenHierarchy | 64 | Look through basetype public and protected static members. |
| InvokeMethod | 256 | Invokes method. |
| CreateInstance | 512 | Creates reflected type instance. |
| GetField | 1024 | Gets field value. |
| SetField | 2048 | Sets field value. |
| GetProperty | 4096 | Gets property value. |
| SetProperty | 8192 | Sets property value. |
| PutDispProperty | 16384 | Puts COM property. |
| PutRefDispProperty | 32768 | Puts COM reference property. |
| ExactBinding | 65536 | Type binding must be exact, without any type changes. |
| SuppressChangeType | 131072 | Not supported. |
| OptionalParamBinding | 262144 | Selects overload based on arguments count. |
| IgnoreReturn | 16777216 | Ignores COM interop return value. |

## See Also

* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
