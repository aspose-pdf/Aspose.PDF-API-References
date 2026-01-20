---
title: System::Net::Cache::HttpCacheAgeControl enum
linktitle: HttpCacheAgeControl
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Cache::HttpCacheAgeControl enum. CacheAgeControl is used to specify preferences with respect of cached item age and freshness in C++.'
type: docs
weight: 300
url: /cpp/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl is used to specify preferences with respect of cached item age and freshness.

```cpp
enum class HttpCacheAgeControl
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | For internal use only. |
| MinFresh | 1 | Content can be taken from the cache if the time remaining before expiration is greater than or equal to the time specified with this value. |
| MaxAge | 2 | Content can be taken from the cache until it is older than the age specified with this value. |
| MaxStale | 4 | Content can be taken from the cache after it has expired until the time specified with this value elapses. |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## See Also

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
