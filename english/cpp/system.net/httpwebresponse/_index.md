---
title: System::Net::HttpWebResponse class
linktitle: HttpWebResponse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::HttpWebResponse class. Represents the HTTP web response. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.net/httpwebresponse/
---
## HttpWebResponse class


Represents the HTTP web response. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebResponse : public System::Net::WebResponse
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the response stream. |
| [get_CharacterSet](./get_characterset/)() | Not implemented. |
| [get_ContentLength](./get_contentlength/)() override | RTTI information. |
| [get_ContentType](./get_contenttype/)() override | Returns the MIME type of the resource. |
| virtual [get_Cookies](./get_cookies/)() | Returns cookies associated with the web response. |
| [get_Headers](./get_headers/)() override | Returns the collection of the headers that are associated with the current response. |
| virtual [get_Method](./get_method/)() | Returns the HTTP method. |
| [get_ResponseUri](./get_responseuri/)() override | Returns the resource's URI. |
| virtual [get_StatusCode](./get_statuscode/)() | Returns the HTTP status code associated with the web response. |
| virtual [get_StatusDescription](./get_statusdescription/)() | Returns the string representation of the status code. |
| [get_SupportsHeaders](./get_supportsheaders/)() override | Returns a value that indicates if the current response supports headers. |
| [GetResponseHeader](./getresponseheader/)(String) | Returns the corresponding value for the specified header name. |
| [GetResponseStream](./getresponsestream/)() override | Returns the response stream. |
| [HttpWebResponse](./httpwebresponse/)(System::SharedPtr\<Http::HttpResponseMessage\>, System::SharedPtr\<Uri\>, System::SharedPtr\<CookieContainer\>) | Constructs a new instance. |
## See Also

* Class [WebResponse](../webresponse/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
