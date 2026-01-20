---
title: System::Net::FileWebRequest class
linktitle: FileWebRequest
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::FileWebRequest class. Provides implementation of the WebRequest abstract class to work with the file system. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.net/filewebrequest/
---
## FileWebRequest class


Provides implementation of the [WebRequest](../webrequest/) abstract class to work with the file system. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileWebRequest : public System::Net::WebRequest
```

## Methods

| Method | Description |
| --- | --- |
| [Abort](./abort/)() override | Aborts the current request. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous operation to get a stream for writing data to the resource. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous request for the resource. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Waits until the specified asynchronous operation to get a stream completes. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Waits until the specified asynchronous request for the resource completes. |
| [FileWebRequest](./filewebrequest/)(System::SharedPtr\<Uri\>) | Constructs a new instance. |
| [get_ContentType](./get_contenttype/)() override | Gets the MIME type of the request. |
| [get_Headers](./get_headers/)() override | Gets the collection of the HTTP headers. |
| [get_Method](./get_method/)() override | Gets the HTTP method. |
| [get_RequestUri](./get_requesturi/)() override | Returns the request URI. |
| [GetResponse](./getresponse/)() override | Returns the web response associated with the current web request. |
| [set_ContentType](./set_contenttype/)(String) override | Sets the MIME type of the request. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Sets the collection of the HTTP headers. |
| [set_Method](./set_method/)(String) override | Sets the HTTP method. |
| [set_Timeout](./set_timeout/)(int) override | RTTI information. |
## See Also

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
