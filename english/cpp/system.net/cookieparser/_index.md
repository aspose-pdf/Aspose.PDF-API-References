---
title: System::Net::CookieParser class
linktitle: CookieParser
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CookieParser class. Used to parse a cookie header and create an instance of the Cookie class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.net/cookieparser/
---
## CookieParser class


Used to parse a cookie header and create an instance of the [Cookie](../cookie/) class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CookieParser : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [CheckQuoted](./checkquoted/)(String) | Checks if the specified string is wrapped in the quotes. |
| [CookieParser](./cookieparser/)(String) | RTTI information. |
| [Get](./get/)() | Returns an instance based on the specified string. |
| [GetServer](./getserver/)() | Gets the server cookie. |
| [GetString](./getstring/)() | Returns the string representation of a cookie header. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
