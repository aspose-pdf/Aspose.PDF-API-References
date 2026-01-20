---
title: System::Net::PathList class
linktitle: PathList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::PathList class. Represents the list of the CookieCollection class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3000
url: /cpp/system.net/pathlist/
---
## PathList class


Represents the list of the [CookieCollection](../cookiecollection/) class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PathList : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)() | Creates a new instance. |
| [get_Count](./get_count/)() const | Returns the number of items. |
| [get_SyncRoot](./get_syncroot/)() const | Returns the object through which the collection is being synchronized. |
| [GetCookiesCount](./getcookiescount/)() | Returns the number of cookies of all collection items. |
| [GetEnumerator](./getenumerator/)() | Returns the enumerator for the current collection. |
| [idx_get](./idx_get/)(String) | Gets the cookie collection by specified path. |
| [idx_set](./idx_set/)(String, System::SharedPtr\<CookieCollection\>) | Sets the cookie collection by specified path. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
