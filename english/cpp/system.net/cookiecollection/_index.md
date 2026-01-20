---
title: System::Net::CookieCollection class
linktitle: CookieCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CookieCollection class. Represents a list of sorted cookies. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.net/cookiecollection/
---
## CookieCollection class


Represents a list of sorted cookies. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CookieCollection : public System::Collections::Generic::ICollection<System::SharedPtr<System::Net::Cookie>>
```

## Enums

| Enum | Description |
| --- | --- |
| [Stamp](./stamp/) | RTTI information. |
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Cookie\>\&) override | Adds a cookie to the collection. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Adds cookies from the specified collection to the current one. |
| [Clear](./clear/)() override | Removes all cookies from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<Cookie\>\&) const override | Checks if the collection contains the specified cookie. |
| [CookieCollection](./cookiecollection/)() | Constructs a new instance. |
| [get_Count](./get_count/)() const override | Gets number of elements in collection. |
| [get_IsOtherVersionSeen](./get_isotherversionseen/)() | Returns a value that indicates if the collection contains a cookie with a version that is not equal to [Cookie::MaxSupportedVersion](../cookie/maxsupportedversion/). |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [idx_get](./idx_get/)(int32_t) | Returns a cookie from the cookie collection at the specified index. |
| [idx_get](./idx_get/)(String) | Returns a cookie from the cookie collection by specified name. |
| [IndexOf](./indexof/)(System::SharedPtr\<Cookie\>) | Returns an index of the specified cookie. |
| [InternalAdd](./internaladd/)(System::SharedPtr\<Cookie\>, bool) | Adds the specified cookie to the collection. |
| [Remove](./remove/)(const System::SharedPtr\<Cookie\>\&) override | Removes the specified cookie from the collection. |
| [RemoveAt](./removeat/)(int32_t) | Removes a cookie at the specified index. |
| [TimeStamp](./timestamp/)(CookieCollection::Stamp) | Updates the timestamp by specified scenario and returns a new value. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
