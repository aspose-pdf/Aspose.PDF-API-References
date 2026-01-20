---
title: System::Net::Http::Headers::HttpRequestHeaders class
linktitle: HttpRequestHeaders
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::HttpRequestHeaders class. Represents the collection of the ''Request'' headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders class


Represents the collection of the 'Request' headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Methods

| Method | Description |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Concatenates the specified HttpHeaders-class instance with the current one. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Adds the known headers to the specified collection. |
| [get_Accept](./get_accept/)() | RTTI information. |
| [get_AcceptCharset](./get_acceptcharset/)() | Returns a value of the 'Accept-Charset' header. |
| [get_AcceptEncoding](./get_acceptencoding/)() | Returns a value of the 'Accept-Encoding' header. |
| [get_AcceptLanguage](./get_acceptlanguage/)() | Returns a value of the 'Accept-Language' header. |
| [get_Authorization](./get_authorization/)() | Gets a value of the 'Authorization' header. |
| [get_CacheControl](./get_cachecontrol/)() | Gets a value of the 'Cache-Control' header. |
| [get_Connection](./get_connection/)() | Returns a value of the 'Connection' header. |
| [get_ConnectionClose](./get_connectionclose/)() | Gets a value that indicates if the 'Connection' header value contains 'Close'. |
| [get_Date](./get_date/)() | Gets a value of the 'Date' header. |
| [get_Expect](./get_expect/)() | Returns value of the 'Expect' header. |
| [get_ExpectContinue](./get_expectcontinue/)() | Gets a value that indicates if the 'Expect' header value contains 'Continue'. |
| [get_From](./get_from/)() | Gets a value of the 'From' header. |
| [get_Host](./get_host/)() | Gets a value of the 'Host' header. |
| [get_IfMatch](./get_ifmatch/)() | Returns a value of the 'If-Match' header. |
| [get_IfModifiedSince](./get_ifmodifiedsince/)() | Gets a value of the 'If-Modified-Since' header. |
| [get_IfNoneMatch](./get_ifnonematch/)() | Returns a value of the 'If-None-Match' header. |
| [get_IfRange](./get_ifrange/)() | Gets a value of the 'If-Range' header. |
| [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | Gets a value of the 'If-Unmodified-Since' header. |
| [get_MaxForwards](./get_maxforwards/)() | Gets a value of the 'Max-Forwards' header. |
| [get_Pragma](./get_pragma/)() | Returns a value of the 'Pragma' header. |
| [get_ProxyAuthorization](./get_proxyauthorization/)() | Gets a value of the 'Proxy-Authorization' header. |
| [get_Range](./get_range/)() | Gets a value of the 'Range' header. |
| [get_Referrer](./get_referrer/)() | Gets a value of the 'Referer' header. |
| [get_TE](./get_te/)() | Returns a value of the 'TE' header. |
| [get_Trailer](./get_trailer/)() | Returns a value of the 'Trailer' header. |
| [get_TransferEncoding](./get_transferencoding/)() | Returns a value of the 'Transfer-Encoding' header. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Gets a value that indicates if the 'Transfer-Encoding' header value contains 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Returns a value of the 'Upgrade' header. |
| [get_UserAgent](./get_useragent/)() | Returns a value of the 'User-Agent' header. |
| [get_Via](./get_via/)() | Returns a value of the 'Via' header. |
| [get_Warning](./get_warning/)() | Returns a value of the 'Warning' header. |
| [HttpRequestHeaders](./httprequestheaders/)() | Constructs a new instance. |
| [set_Authorization](./set_authorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Sets a value of the 'Authorization' header. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Sets a value of the 'Cache-Control' header. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Sets a value that indicates if the 'Connection' header value contains 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Sets a value of the 'Date' header. |
| [set_ExpectContinue](./set_expectcontinue/)(Nullable\<bool\>) | Sets a value that indicates if the 'Expect' header value contains 'Continue'. |
| [set_From](./set_from/)(String) | Sets a value of the 'From' header. |
| [set_Host](./set_host/)(String) | Sets a value of the 'Host' header. |
| [set_IfModifiedSince](./set_ifmodifiedsince/)(Nullable\<DateTimeOffset\>) | Sets a value of the 'If-Modified-Since' header. |
| [set_IfRange](./set_ifrange/)(System::SharedPtr\<RangeConditionHeaderValue\>) | Sets a value of the 'If-Range' header. |
| [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)(Nullable\<DateTimeOffset\>) | Sets a value of the 'If-Unmodified-Since' header. |
| [set_MaxForwards](./set_maxforwards/)(Nullable\<int32_t\>) | Sets a value of the 'Max-Forwards' header. |
| [set_ProxyAuthorization](./set_proxyauthorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Sets a value of the 'Proxy-Authorization' header. |
| [set_Range](./set_range/)(System::SharedPtr\<RangeHeaderValue\>) | Sets a value of the 'Range' header. |
| [set_Referrer](./set_referrer/)(System::SharedPtr\<Uri\>) | Sets a value of the 'Referer' header. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Sets a value that indicates if the 'Transfer-Encoding' header value contains 'Chunked'. |
## See Also

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
