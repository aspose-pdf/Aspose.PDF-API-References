---
title: System::Net::WebRequest class
linktitle: WebRequest
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest class. Represents a web request. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3800
url: /cpp/system.net/webrequest/
---
## WebRequest class


Represents a web request. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebRequest : public virtual System::Object
```

## Nested classes

* Class [HttpRequestCreator](./httprequestcreator/)
* Class [WebRequestPrefixElement](./webrequestprefixelement/)
## Methods

| Method | Description |
| --- | --- |
| virtual [Abort](./abort/)() | Aborts the current request. |
| virtual [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous operation to get a stream for writing data to the resource. |
| virtual [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) | Initiates an asynchronous request for the resource. |
| static [Create](./create/)(String) | Creates a new instance of the [WebRequest](./) class using the specified URI. |
| static [Create](./create/)(System::SharedPtr\<Uri\>) | Creates a new instance of the [WebRequest](./) class using the specified URI. |
| static [CreateDefault](./createdefault/)(System::SharedPtr\<Uri\>) | Creates a [WebRequest](./) descendant for the specified URI scheme. |
| static [CreateHttp](./createhttp/)(String) | Creates a new instance of the [WebRequest](./) class using the specified URI. |
| static [CreateHttp](./createhttp/)(System::SharedPtr\<Uri\>) | Creates a new instance of the [WebRequest](./) class using the specified URI. |
| virtual [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous operation to get a stream completes. |
| virtual [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) | Waits until the specified asynchronous request for the resource completes. |
| virtual [get_CachePolicy](./get_cachepolicy/)() | Gets the cache policy. |
| virtual [get_ConnectionGroupName](./get_connectiongroupname/)() | Gets the name of the connection group. |
| virtual [get_ContentLength](./get_contentlength/)() | Gets the number of bytes of the request data to sent. |
| virtual [get_ContentType](./get_contenttype/)() | Gets the MIME type of the request. |
| virtual [get_Credentials](./get_credentials/)() | Gets authentication information that is associated with the current request. |
| static [get_DefaultWebProxy](./get_defaultwebproxy/)() | Gets the global HTTP proxy. |
| virtual [get_Headers](./get_headers/)() | Gets the collection of the HTTP headers. |
| virtual [get_Method](./get_method/)() | Gets the HTTP method. |
| virtual [get_PreAuthenticate](./get_preauthenticate/)() | Gets a value that indicates if the request must be pre-authenticated. |
| static [get_PrefixList](./get_prefixlist/)() | Gets the prefix list. |
| virtual [get_Proxy](./get_proxy/)() | Gets the HTTP proxy. |
| virtual [get_RequestUri](./get_requesturi/)() | Returns the request URI. |
| virtual [get_Timeout](./get_timeout/)() | Gets an amount of time in milliseconds after which the request will be timed out. |
| virtual [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Gets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
| virtual [GetRequestStream](./getrequeststream/)() | Returns the stream for writing data to the resource. |
| virtual [GetResponse](./getresponse/)() | Returns the web response associated with the current web request. |
| static [RegisterPrefix](./registerprefix/)(String, System::SharedPtr\<IWebRequestCreate\>) | Registers the [WebRequest](./) descendant for the specified URI. |
| virtual [set_CachePolicy](./set_cachepolicy/)(System::SharedPtr\<System::Net::Cache::RequestCachePolicy\>) | Sets the cache policy. |
| virtual [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) | Sets the name of the connection group. |
| virtual [set_ContentLength](./set_contentlength/)(int64_t) | Sets the number of bytes of the request data to sent. |
| virtual [set_ContentType](./set_contenttype/)(String) | Sets the MIME type of the request. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Sets authentication information that is associated with the current request. |
| static [set_DefaultWebProxy](./set_defaultwebproxy/)(System::SharedPtr\<IWebProxy\>) | Sets the global HTTP proxy. |
| virtual [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) | Sets the collection of the HTTP headers. |
| virtual [set_Method](./set_method/)(String) | Sets the HTTP method. |
| virtual [set_PreAuthenticate](./set_preauthenticate/)(bool) | Sets a value that indicates if the request must be pre-authenticated. |
| static [set_PrefixList](./set_prefixlist/)(System::SharedPtr\<Collections::Generic::List\<System::SharedPtr\<WebRequest::WebRequestPrefixElement\>\>\>) | Sets the prefix list. |
| virtual [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Sets the HTTP proxy. |
| virtual [set_Timeout](./set_timeout/)(int32_t) | Sets an amount of time in milliseconds after which the request will be timed out. |
| virtual [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Sets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
