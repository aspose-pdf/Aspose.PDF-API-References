---
title: System::Net::Http::Headers::HttpContentHeaders class
linktitle: HttpContentHeaders
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::HttpContentHeaders class. Represents the collection of the ''Content'' headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.net.http.headers/httpcontentheaders/
---
## HttpContentHeaders class


Represents the collection of the 'Content' headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpContentHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Methods

| Method | Description |
| --- | --- |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Adds the known headers to the specified collection. |
| [get_Allow](./get_allow/)() | RTTI information. |
| [get_ContentDisposition](./get_contentdisposition/)() | Gets a value of the 'Content-Disposition' header. |
| [get_ContentEncoding](./get_contentencoding/)() | Gets a value of the 'Content-Encoding' header. |
| [get_ContentLanguage](./get_contentlanguage/)() | Gets a value of the 'Content-Language' header. |
| [get_ContentLength](./get_contentlength/)() | Gets a value of the 'Content-Length' header. |
| [get_ContentLocation](./get_contentlocation/)() | Gets a value of the 'Content-Location' header. |
| [get_ContentMD5](./get_contentmd5/)() | Gets a value of the 'Content-MD5' header. |
| [get_ContentRange](./get_contentrange/)() | Gets a value of the 'Content-Range' header. |
| [get_ContentType](./get_contenttype/)() | Gets a value of the 'Content-Type' header. |
| [get_Expires](./get_expires/)() | Gets a value of the 'Expires' header. |
| [get_LastModified](./get_lastmodified/)() | Gets a value of the 'Last-Modified' header. |
| [HttpContentHeaders](./httpcontentheaders/)(HeaderFunc\<Nullable\<int64_t\>\>) | Constructs a new instance. |
| [set_ContentDisposition](./set_contentdisposition/)(System::SharedPtr\<ContentDispositionHeaderValue\>) | Sets a value of the 'Content-Disposition' header. |
| [set_ContentLength](./set_contentlength/)(Nullable\<int64_t\>) | Sets a value of the 'Content-Length' header. |
| [set_ContentLocation](./set_contentlocation/)(System::SharedPtr\<Uri\>) | Sets a value of the 'Content-Location' header. |
| [set_ContentMD5](./set_contentmd5/)(System::ArrayPtr\<uint8_t\>) | Sets a value of the 'Content-MD5' header. |
| [set_ContentRange](./set_contentrange/)(System::SharedPtr\<ContentRangeHeaderValue\>) | Sets a value of the 'Content-Range' header. |
| [set_ContentType](./set_contenttype/)(System::SharedPtr\<MediaTypeHeaderValue\>) | Sets a value of the 'Content-Type' header. |
| [set_Expires](./set_expires/)(Nullable\<DateTimeOffset\>) | Sets a value of the 'Expires' header. |
| [set_LastModified](./set_lastmodified/)(Nullable\<DateTimeOffset\>) | Sets a value of the 'Last-Modified' header. |
## See Also

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
