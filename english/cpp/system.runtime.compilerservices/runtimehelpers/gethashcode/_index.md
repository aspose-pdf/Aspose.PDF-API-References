---
title: System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode method
linktitle: GetHashCode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode method. Gets hash code on arbitrary type. Calls Object::GetHashCode() to do so in C++.'
type: docs
weight: 100
url: /cpp/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode method


Gets hash code on arbitrary type. Calls [Object::GetHashCode()](../../../system/object/gethashcode/) to do so.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```


| Parameter | Description |
| --- | --- |
| T | Type to get hash code for. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<T\> const\& | [Object](../../../system/object/) to get information from. |

### ReturnValue

Hash code value as calcualted by target implementation.

## See Also

* Class [SmartPtr](../../../system/smartptr/)
* Class [RuntimeHelpers](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Library [Aspose.PDF for C++](../../../)
