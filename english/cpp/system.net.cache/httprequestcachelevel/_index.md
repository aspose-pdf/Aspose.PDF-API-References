---
title: System::Net::Cache::HttpRequestCacheLevel enum
linktitle: HttpRequestCacheLevel
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Cache::HttpRequestCacheLevel enum. The enum describes cache settings for HTTP in C++.'
type: docs
weight: 400
url: /cpp/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


The enum describes cache settings for HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Satisfies a request for a resource either by using the cached copy of the resource or by sending a request for the resource to the server. |
| BypassCache | 1 | Satisfies a request by using the server. |
| CacheOnly | 2 | Always uses the client cache to get a resource. |
| CacheIfAvailable | 3 | Satisfies a request for a resource from the cache if the resource is available, otherwise sends a request to the server. |
| Revalidate | 4 | Using a resource local copy if the client timestamp is the same as the timestamp of the resource on the server. Otherwise, a resource is downloaded from a server. |
| Reload | 5 | A resource is always downloaded from the server. |
| NoCacheNoStore | 6 | Never satisfies a request by using resources from the cache and does not cache resources. |
| CacheOrNextCacheOnly | 7 | Satisfies a request for a resource either from the local computer's cache or from a remote cache on the LAN. |
| Refresh | 8 | Satisfies a request by using the server or a cache other than the local cache. |

## See Also

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
