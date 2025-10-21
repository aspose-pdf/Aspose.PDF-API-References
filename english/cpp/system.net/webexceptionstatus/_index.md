---
title: System::Net::WebExceptionStatus enum
linktitle: WebExceptionStatus
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebExceptionStatus enum. Enumerates the status codes of the WebException class in C++.'
type: docs
weight: 4900
url: /cpp/system.net/webexceptionstatus/
---
## WebExceptionStatus enum


Enumerates the status codes of the [WebException](../webexception/) class.

```cpp
enum class WebExceptionStatus
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Success | 0 | No errors occurred. |
| NameResolutionFailure | 1 | The name resolver service could not resolve the host name. |
| ConnectFailure | 2 | The remote service point could not be contacted at the transport level. |
| ReceiveFailure | 3 | A complete response is not received from the remote server. |
| SendFailure | 4 | A complete request could not be sent to the remote server. |
| PipelineFailure | 5 | The request was a pipelined request and the connection was closed before the response was received. |
| RequestCanceled | 6 | The request was canceled or an unclassifiable error occurred. |
| ProtocolError | 7 | The response received from the server was complete but indicated a protocol-level error. |
| ConnectionClosed | 8 | The connection was prematurely closed. |
| TrustFailure | 9 | A server certificate could not be validated. |
| SecureChannelFailure | 10 | An error occurred while establishing a connection using SSL. |
| ServerProtocolViolation | 11 | The server response was not a valid HTTP response. |
| KeepAliveFailure | 12 | The connection for a request that specifies the 'Keep-Alive' header was closed unexpectedly. |
| Pending | 13 | An internal asynchronous request is pending. |
| Timeout | 14 | No response was received during the time-out period for a request. |
| ProxyNameResolutionFailure | 15 | The name resolver service could not resolve the proxy host name. |
| UnknownError | 16 | An exception of unknown type has occurred. |
| MessageLengthLimitExceeded | 17 | A message that exceeded the specified limit was received. |
| CacheEntryNotFound | 18 | The specified cache entry was not found. |
| RequestProhibitedByCachePolicy | 19 | The request was not permitted by the cache policy. |
| RequestProhibitedByProxy | 20 | This request was not permitted by the proxy. |

## See Also

* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
