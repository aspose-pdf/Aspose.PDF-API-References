---
title: System::Net::HttpWebRequest class
linktitle: HttpWebRequest
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::HttpWebRequest class. Represents the HTTP web request. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system.net/httpwebrequest/
---
## HttpWebRequest class


Represents the HTTP web request. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Methods

| Method | Description |
| --- | --- |
| [Abort](./abort/)() override | Aborts the current request. |
| virtual [AddRange](./addrange/)(int32_t) | Adds the 'Range' header to the current request. |
| virtual [AddRange](./addrange/)(System::String, int32_t, int32_t) | Adds the 'Range' header to the current request. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous operation to get a stream for writing data to the resource. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous request for the resource. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Waits until the specified asynchronous operation to get a stream completes. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Waits until the specified asynchronous request for the resource completes. |
| [get_Accept](./get_accept/)() | Gets the 'Accept' HTTP header value. |
| virtual [get_AllowAutoRedirect](./get_allowautoredirect/)() | Gets a value that indicates if the request should follow redirections. |
| virtual [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Gets a value indicates if the data received from the resource must be buffered. |
| virtual [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Gets a value that indicates if buffering is enabled for sending data. |
| virtual [get_ClientCertificates](./get_clientcertificates/)() | Gets the collection of the certificates that are associated with the current request. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() override | Gets the name of the connection group. |
| [get_ContentLength](./get_contentlength/)() override | Gets the number of bytes of the request data to sent. |
| [get_ContentType](./get_contenttype/)() override | Gets the MIME type of the request. |
| [get_ContinueTimeout](./get_continuetimeout/)() | Gets a timeout to wait until the 100-Continue status code is received. |
| virtual [get_CookieContainer](./get_cookiecontainer/)() | Gets a cookie container associated with the current web request. |
| [get_Credentials](./get_credentials/)() override | Gets authentication information that is associated with the current request. |
| virtual [get_HaveResponse](./get_haveresponse/)() | Returns a value that indicates if a response is received. |
| [get_Headers](./get_headers/)() override | Gets the collection of the HTTP headers. |
| virtual [get_KeepAlive](./get_keepalive/)() | Gets a value that indicates if the current request must contain the 'Keep-Alive' header. |
| virtual [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Gets a maximum number of allowed redirections. |
| [get_Method](./get_method/)() override | Gets the HTTP method. |
| [get_PreAuthenticate](./get_preauthenticate/)() override | Gets a value that indicates if the request must be pre-authenticated. |
| [get_Proxy](./get_proxy/)() override | Gets the HTTP proxy. |
| virtual [get_Referer](./get_referer/)() | Gets a value of the 'Referer' header. |
| [get_RequestUri](./get_requesturi/)() override | Returns the request URI. |
| virtual [get_SendChunked](./get_sendchunked/)() | Gets a value that indicates if data must be sent in segments. |
| [get_ServicePoint](./get_servicepoint/)() | Returns a service point that represents the network connection to the resource. |
| virtual [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Returns a value that indicates if the current request can use a cookie container. |
| [get_Timeout](./get_timeout/)() override | Gets an amount of time in milliseconds after which the request will be timed out. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Gets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
| virtual [get_UserAgent](./get_useragent/)() | Gets a value of the 'User-Agent' header. |
| [GetRequestStream](./getrequeststream/)() override | Returns the stream for writing data to the resource. |
| [GetResponse](./getresponse/)() override | Returns the web response associated with the current web request. |
| [HttpWebRequest](./httpwebrequest/)(System::SharedPtr\<Uri\>) | Constructs a new instance. |
| [set_Accept](./set_accept/)(String) | Sets the 'Accept' HTTP header value. |
| virtual [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Sets a value that indicates if the request should follow redirections. |
| virtual [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(bool) | Sets a value indicates if the data received from the resource must be buffered. |
| virtual [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(bool) | Sets a value that indicates if buffering is enabled for sending data. |
| virtual [set_ClientCertificates](./set_clientcertificates/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>) | Sets the collection of the certificates that are associated with the current request. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) override | Sets the name of the connection group. |
| [set_ContentLength](./set_contentlength/)(int64_t) override | Sets the number of bytes of the request data to sent. |
| [set_ContentType](./set_contenttype/)(String) override | Sets the MIME type of the request. |
| [set_ContinueTimeout](./set_continuetimeout/)(int32_t) | Sets a timeout to wait until the 100-Continue status code is received. |
| virtual [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Sets a cookie container associated with the current web request. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) override | Sets authentication information that is associated with the current request. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Sets the collection of the HTTP headers. |
| virtual [set_KeepAlive](./set_keepalive/)(bool) | Sets a value that indicates if the current request must contain the 'Keep-Alive' header. |
| virtual [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Sets a maximum number of allowed redirections. |
| [set_Method](./set_method/)(String) override | Sets the HTTP method. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) override | Sets a value that indicates if the request must be pre-authenticated. |
| [set_ProtocolVersion](./set_protocolversion/)(System::Version) | RTTI information. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) override | Sets the HTTP proxy. |
| virtual [set_Referer](./set_referer/)(System::String) | Sets a value of the 'Referer' header. |
| virtual [set_SendChunked](./set_sendchunked/)(bool) | Sets a value that indicates if data must be sent in segments. |
| [set_Timeout](./set_timeout/)(int) override | Sets an amount of time in milliseconds after which the request will be timed out. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) override | Sets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
| virtual [set_UserAgent](./set_useragent/)(System::String) | Sets a value of the 'User-Agent' header. |
## See Also

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
