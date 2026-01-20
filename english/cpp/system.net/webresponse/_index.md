---
title: System::Net::WebResponse class
linktitle: WebResponse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebResponse class. Represents a web response. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 4000
url: /cpp/system.net/webresponse/
---
## WebResponse class


Represents a web response. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebResponse : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | Closes the response stream. |
| [Dispose](./dispose/)() override | Does nothing. |
| virtual [get_ContentLength](./get_contentlength/)() | RTTI information. |
| virtual [get_ContentType](./get_contenttype/)() | Returns the MIME type of the resource. |
| virtual [get_Headers](./get_headers/)() | Returns the collection of the headers that are associated with the current response. |
| virtual [get_ResponseUri](./get_responseuri/)() | Returns the resource's URI. |
| virtual [get_SupportsHeaders](./get_supportsheaders/)() | Returns a value that indicates if the current response supports headers. |
| virtual [GetResponseStream](./getresponsestream/)() | Returns the response stream. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
