---
title: System::Net::Http::HttpMessageHandler class
linktitle: HttpMessageHandler
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpMessageHandler class. Represents a base type for the HTTP message handlers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.net.http/httpmessagehandler/
---
## HttpMessageHandler class


Represents a base type for the HTTP message handlers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpMessageHandler : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Does nothing. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | RTTI information. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
