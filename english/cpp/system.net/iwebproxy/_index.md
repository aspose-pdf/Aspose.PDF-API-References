---
title: System::Net::IWebProxy class
linktitle: IWebProxy
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::IWebProxy class. This interface used for implementation of proxy access to the WebRequest class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2700
url: /cpp/system.net/iwebproxy/
---
## IWebProxy class


This interface used for implementation of proxy access to the [WebRequest](../webrequest/) class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IWebProxy : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_Credentials](./get_credentials/)() | RTTI information. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Returns the proxy URI. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Returns a value that indicates if the proxy must not be used for the specified host. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Sets credentials for authentication on the proxy server. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
