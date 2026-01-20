---
title: System::ObjectExt::UnknownIsNull method
linktitle: UnknownIsNull
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::UnknownIsNull method. Checks whether unknown type object is nullptr. Overload for non-scalar types in C++.'
type: docs
weight: 1700
url: /cpp/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) method


Checks whether unknown type object is nullptr. Overload for non-scalar types.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### ReturnValue

True if 'obj == nullptr' is true, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownIsNull(T) method


Checks whether unknown type object is nullptr. Overload for scalar types.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### ReturnValue

Always returns false.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
