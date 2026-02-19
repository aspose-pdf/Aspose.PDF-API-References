---
title: System::setter_increment_wrap method
linktitle: setter_increment_wrap
second_title: Aspose.PDF for C++ API Reference
description: 'System::setter_increment_wrap method. Translator translates C#''s increment expressions targeting class'' property that has setter and getter defined, into invocation of this function in C++.'
type: docs
weight: 39100
url: /cpp/system/setter_increment_wrap/
---
## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parameter | Description |
| --- | --- |
| T | The type of the property |
| Host | - class of instance to be modified |
| HostGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | A pointer to an object whose property is to be incremented |
| pGetter | T(HostGet::*)() | Function pointer pointing to the property's getter method |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter method |

### ReturnValue

The incremented value of the property

## See Also

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_increment_wrap(T(*)(), void(*)(T)) method


Translator translates C#'s increment expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parameter | Description |
| --- | --- |
| T | The type of the property |

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Function pointer pointing to the property's getter free function |
| pSetter | void(*)(T) | Function pointer pointing to the property's setter free function |

### ReturnValue

The incremented value of the property

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
