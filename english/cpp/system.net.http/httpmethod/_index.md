---
title: System::Net::Http::HttpMethod class
linktitle: HttpMethod
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpMethod class. Represents an HTTP method. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.net.http/httpmethod/
---
## HttpMethod class


Represents an HTTP method. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpMethod : public System::IEquatable<System::SharedPtr<System::Net::Http::HttpMethod>>
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<HttpMethod\>) override | Determines if the the current and specified objects are equal. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static [get_Delete](./get_delete/)() | Returns the 'DELETE' HTTP method. |
| static [get_Get](./get_get/)() | Returns the 'GET' HTTP method. |
| static [get_Head](./get_head/)() | Returns the 'HEAD' HTTP method. |
| [get_Method](./get_method/)() | Returns a string representation of the HTTP method. |
| static [get_Options](./get_options/)() | Returns the 'OPTIONS' HTTP method. |
| static [get_Post](./get_post/)() | Returns the 'POST' HTTP method. |
| static [get_Put](./get_put/)() | Returns the 'PUT' HTTP method. |
| static [get_Trace](./get_trace/)() | Returns the 'TRACE' HTTP method. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [HttpMethod](./httpmethod/)(String) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
