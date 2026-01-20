---
title: System::Net::CookieContainer class
linktitle: CookieContainer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CookieContainer class. Provides a container for the CookieCollection-class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.net/cookiecontainer/
---
## CookieContainer class


Provides a container for the CookieCollection-class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CookieContainer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Cookie\>) | Adds a cookie to the collection. |
| [Add](./add/)(System::SharedPtr\<Cookie\>, bool) | Adds a cookie to the collection. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Copies cookies from the specified collection to the current one. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) | Adds a cookie for the specified URI. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) | Copies cookies from the specified collection for the specified URI to the current collection. |
| [CookieContainer](./cookiecontainer/)() | Constructs a new instance. |
| [CookieContainer](./cookiecontainer/)(int32_t) | Constructs a new instance. |
| [CookieContainer](./cookiecontainer/)(int32_t, int32_t, int32_t) | Constructs a new instance. |
| [CookieCutter](./cookiecutter/)(System::SharedPtr\<Uri\>, String, String, bool) | Copies cookies from the specified HTTP header for the specified URI. |
| [get_Capacity](./get_capacity/)() | Gets the collection capacity. |
| [get_Count](./get_count/)() | Returns the number of the collection's items. |
| [get_MaxCookieSize](./get_maxcookiesize/)() | Gets the maximum cookie size. |
| [get_PerDomainCapacity](./get_perdomaincapacity/)() | Gets the collection capacity per domain. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>) | Return an HTTP header that contains cookies associated with the specified URI. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>, String\&) | Return an HTTP header that contains cookies associated with the specified URI. |
| [GetCookies](./getcookies/)(System::SharedPtr\<Uri\>) | Returns a collection of cookies that are associated with the specified URI. |
| [InternalGetCookies](./internalgetcookies/)(System::SharedPtr\<Uri\>) | Returns a collection of cookies that are associated with the specified URI. |
| [IsLocalDomain](./islocaldomain/)(String) | Checks if the specified domain is localhost. |
| [set_Capacity](./set_capacity/)(int32_t) | Sets the collection capacity. |
| [set_MaxCookieSize](./set_maxcookiesize/)(int32_t) | Sets the maximum cookie size. |
| [set_PerDomainCapacity](./set_perdomaincapacity/)(int32_t) | Sets the collection capacity per domain. |
| [SetCookies](./setcookies/)(System::SharedPtr\<Uri\>, String) | Copies cookies from the specified header to the collection and associates them with the specified URI. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | The maximum cookie size. |
| static [DefaultCookieLimit](./defaultcookielimit/) | RTTI information. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | The maximum number of collection items per domain. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
