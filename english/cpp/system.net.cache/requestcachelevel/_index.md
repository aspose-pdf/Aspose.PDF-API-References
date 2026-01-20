---
title: System::Net::Cache::RequestCacheLevel enum
linktitle: RequestCacheLevel
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Cache::RequestCacheLevel enum. The enum describes cache settings applicable for any WebRequest in C++.'
type: docs
weight: 500
url: /cpp/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum


The enum describes cache settings applicable for any [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Satisfies a request for a resource either by using the cached copy of the resource or by sending a request for the resource to the server. |
| BypassCache | 1 | Satisfies a request by using the server. No entries are taken from the cache. |
| CacheOnly | 2 | Satisfies a request for a resource only from the cache. [WebException](../../system.net/webexception/) will be thrown when a resource is not in the client cache. |
| CacheIfAvailable | 3 | Satisfies a request for a resource from the cache if the resource is available, otherwise sends a request to the server. |
| Revalidate | 4 | Using a resource local copy if the client timestamp is the same as the timestamp of the resource on the server. Otherwise, a resource is downloaded from a server. |
| Reload | 5 | A resource is always downloaded from the server. |
| NoCacheNoStore | 6 | Never satisfies a request by using resources from the cache and does not cache resources. |

## See Also

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
