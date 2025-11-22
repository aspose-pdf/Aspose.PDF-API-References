---
title: System::setter_decrement_wrap method
linktitle: setter_decrement_wrap
second_title: Aspose.PDF for C++ API Reference
description: 'System::setter_decrement_wrap method. Translator translates C#''s pre-decrement expressions targeting instance''s property that has setter and getter defined, into invocation of this function (overload for const getter) in C++.'
type: docs
weight: 37900
url: /cpp/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) method


Translator translates C#'s pre-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


| Parameter | Description |
| --- | --- |
| T | The type of the property. |
| Host | - class of instance to be modified |
| HostConstGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostConstGet::*)() const | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### ReturnValue

The value of the property before incrementing

## See Also

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Translator translates C#'s pre-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for non-const getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parameter | Description |
| --- | --- |
| T | The type of the property. |
| Host | - class of instance to be modified |
| HostGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostGet::*)() | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### ReturnValue

The value of the property before incrementing

## See Also

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_decrement_wrap(T(*)(), void(*)(T)) method


Translator translates C#'s pre-decrement expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parameter | Description |
| --- | --- |
| T | The type of the property |

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Function pointer pointing to the property's getter free function |
| pSetter | void(*)(T) | Function pointer pointing to the property's setter free function |

### ReturnValue

The value of the property before incrementing

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
