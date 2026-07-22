---
title: "System::Net::Cache::HttpCacheAgeControl enum"
linktitle: "HttpCacheAgeControl"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Cache::HttpCacheAgeControl enum. CacheAgeControl används för att ange preferenser avseende cachelagda objekts ålder och färskhet i C++."
type: docs
weight: 300
url: /sv/cpp/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl används för att ange preferenser med avseende på cachade objekts ålder och fräschör.

```cpp
enum class HttpCacheAgeControl
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Endast för internt bruk. |
| MinFresh | 1 | Innehållet kan hämtas från cachen om den återstående tiden före utgången är större än eller lika med den tid som anges med detta värde. |
| MaxAge | 2 | Innehållet kan hämtas från cachen tills det är äldre än den ålder som anges med detta värde. |
| MaxStale | 4 | Innehållet kan hämtas från cachen efter att det har gått ut tills den tid som anges med detta värde har förflutit. |
| MaxAgeAndMinFresh | 3 | MaxAge och MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge och MaxStale. |

## Se även

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
