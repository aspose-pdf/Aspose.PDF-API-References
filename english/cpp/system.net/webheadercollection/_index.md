---
title: System::Net::WebHeaderCollection class
linktitle: WebHeaderCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebHeaderCollection class. Represents the collection of the protocol headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3600
url: /cpp/system.net/webheadercollection/
---
## WebHeaderCollection class


Represents the collection of the protocol headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebHeaderCollection : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(String, String) | Adds the specified pair of the header name and the header value to the collection. |
| [Add](./add/)(HttpResponseHeader, String) | Adds the specified pair of the header and the header value to the collection. |
| [Add](./add/)(HttpRequestHeader, String) | Adds the specified pair of the header and the header value to the collection. |
| [AllKeys](./allkeys/)() | Returns a collection of header names that are stored in the collection. |
| [get_Count](./get_count/)() const | Returns a number of elements in the collection. |
| [get_Keys](./get_keys/)() | Returns a collection of header names that are stored in the collection. |
| [GetKey](./getkey/)(int) | Returns a key at the specified index. |
| [GetValues](./getvalues/)(String) | Returns the collection of the header values. |
| [idx_get](./idx_get/)(HttpRequestHeader) | Gets the header value using the specified request's header. |
| [idx_get](./idx_get/)(HttpResponseHeader) | Gets the header value using the specified response's header. |
| [idx_get](./idx_get/)(String) | Gets the header value using the specified header name. |
| [idx_set](./idx_set/)(HttpRequestHeader, String) | Sets the header value of the specified header. |
| [idx_set](./idx_set/)(HttpResponseHeader, String) | Sets the header value using the specified response's header. |
| [idx_set](./idx_set/)(String, String) | Sets the header value using the specified header name. |
| static [IsRestricted](./isrestricted/)(const String\&) | Tests whether the specified HTTP header can be set for the request. |
| [Remove](./remove/)(String) | Removes the header by the specified header name. |
| [Remove](./remove/)(HttpResponseHeader) | Removes the specified response's header. |
| [Remove](./remove/)(HttpRequestHeader) | Removes the specified request's header. |
| [Set](./set/)(String, String) | Sets the value of the specified header. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [WebHeaderCollection](./webheadercollection/)() | Constructs a new instance. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
