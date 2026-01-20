---
title: System::Net::Http::HttpResponseMessage class
linktitle: HttpResponseMessage
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpResponseMessage class. Represents an HTTP response message. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.net.http/httpresponsemessage/
---
## HttpResponseMessage class


Represents an HTTP response message. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the current instance. This method also disposes content of the HTTP response. |
| [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Checks the status code. [HttpRequestException](../httprequestexception/) will be thrown when the status code doesn't belong to 2xx. |
| [get_Content](./get_content/)() const | Gets content of the HTTP response. |
| [get_Headers](./get_headers/)() const | Returns the HTTP content headers. |
| [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Checks if the status code indicates that the action requested by the client was received, understood, and accepted. |
| [get_ReasonPhrase](./get_reasonphrase/)() const | Gets the Reason-Phrase that is sent by servers together with the status code. |
| [get_RequestMessage](./get_requestmessage/)() const | Gets the HTTP request message. |
| [get_StatusCode](./get_statuscode/)() const | Gets the HTTP status code. |
| [get_Version](./get_version/)() const | RTTI information. |
| [HttpResponseMessage](./httpresponsemessage/)() | Constructs a new instance. |
| [HttpResponseMessage](./httpresponsemessage/)(HttpStatusCode) | Constructs a new instance. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Sets content of the HTTP response. |
| [set_ReasonPhrase](./set_reasonphrase/)(String) | Sets the Reason-Phrase that is sent by servers together with the status code. |
| [set_RequestMessage](./set_requestmessage/)(System::SharedPtr\<HttpRequestMessage\>) | Sets the HTTP request message. |
| [set_StatusCode](./set_statuscode/)(HttpStatusCode) | Sets the HTTP status code. |
| [set_Version](./set_version/)(System::Version) | Sets the HTTP version. |
| [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
