---
title: System::ObjectExt::ArrayInitializerCast method
linktitle: ArrayInitializerCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::ArrayInitializerCast method. Converts array fundamental values (which C# does implicitly but C++ apparently does not) in C++.'
type: docs
weight: 100
url: /cpp/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast method


Converts array fundamental values (which C# does implicitly but C++ apparently does not).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


| Parameter | Description |
| --- | --- |
| To | Target type. |
| From | Source types. |

| Parameter | Type | Description |
| --- | --- | --- |
| args | From ... | Values to convert and push to target array. |

### ReturnValue

[Array](../../array/) containing converted copies of all arguments in the same order.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
