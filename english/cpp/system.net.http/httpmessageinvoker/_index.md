---
title: System::Net::Http::HttpMessageInvoker class
linktitle: HttpMessageInvoker
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpMessageInvoker class. Allows applications to call the Send method on an HTTP handler chain. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.net.http/httpmessageinvoker/
---
## HttpMessageInvoker class


Allows applications to call the Send method on an HTTP handler chain. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpMessageInvoker : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the current instance. This method also disposes the handler if required. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>) | RTTI information. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Constructs a new instance. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | Sends the specified request. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
