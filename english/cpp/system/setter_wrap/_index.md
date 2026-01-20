---
title: System::setter_wrap method
linktitle: setter_wrap
second_title: Aspose.PDF for C++ API Reference
description: 'System::setter_wrap method. Overload for instance setter functions with type conversion in C++.'
type: docs
weight: 42200
url: /cpp/system/setter_wrap/
---
## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) method


Overload for instance setter functions with type conversion.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```


| Parameter | Description |
| --- | --- |
| T | Value type. |
| T2 | Type expected by setter function. |
| Host | Instance type. |
| HostSet | - Host itself, or it's base type, where property's setter is defined. |

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | [Object](../object/) to call setter function for. |
| pSetter | void(HostSet::*)(T2) | Setter function reference. |
| value | T | Value to set. |

### ReturnValue

set value.

## See Also

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_wrap(void(*)(T2), T) method


Overload for static setter functions with type conversion.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```


| Parameter | Description |
| --- | --- |
| T | Value type. |
| T2 | Type expected by setter function. |

| Parameter | Type | Description |
| --- | --- | --- |
| pSetter | void(*)(T2) | Static setter function reference. |
| value | T | Value to set. |

### ReturnValue

set value.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
