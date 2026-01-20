---
title: System::Net::Http::HttpClient class
linktitle: HttpClient
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpClient class. Represents a base class of an HTTP client for sending requests and receiving responses. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.net.http/httpclient/
---
## HttpClient class


Represents a base class of an HTTP client for sending requests and receiving responses. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## Methods

| Method | Description |
| --- | --- |
| [CancelPendingRequests](./cancelpendingrequests/)() | Cancels all pending requests. |
| [get_BaseAddress](./get_baseaddress/)() | Gets the base address of the resource that is used for sending requests. |
| [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | RTTI information. |
| [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | Gets the maximum number of bytes of response content. |
| [get_Timeout](./get_timeout/)() | Gets the timespan to wait before the request times out. |
| [HttpClient](./httpclient/)() | Constructs a new instance. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>) | Constructs a new instance. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Constructs a new instance. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) | Sends the specified HTTP request. |
| [set_BaseAddress](./set_baseaddress/)(System::SharedPtr\<Uri\>) | Sets the base address of the resource that is used for sending requests. |
| [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(int64_t) | Sets the maximum number of bytes of response content. |
| [set_Timeout](./set_timeout/)(TimeSpan) | Sets the timespan to wait before the request times out. |
## See Also

* Class [HttpMessageInvoker](../httpmessageinvoker/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
