---
title: System::Net::FileWebResponse class
linktitle: FileWebResponse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::FileWebResponse class. Provides implementation of the WebResponse abstract class to work with the file system. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.net/filewebresponse/
---
## FileWebResponse class


Provides implementation of the [WebResponse](../webresponse/) abstract class to work with the file system. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileWebResponse : public System::Net::WebResponse
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the response stream. |
| [FileWebResponse](./filewebresponse/)(System::SharedPtr\<Uri\>) | Constructs a new instance. |
| [get_ContentLength](./get_contentlength/)() override | RTTI information. |
| [get_ContentType](./get_contenttype/)() override | Returns the MIME type of the resource. |
| [get_Headers](./get_headers/)() override | Returns the collection of the headers that are associated with the current response. |
| [get_ResponseUri](./get_responseuri/)() override | Returns the resource's URI. |
| [get_SupportsHeaders](./get_supportsheaders/)() override | Returns a value that indicates if the current response supports headers. |
| [GetResponseStream](./getresponsestream/)() override | Returns the response stream. |
## See Also

* Class [WebResponse](../webresponse/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
