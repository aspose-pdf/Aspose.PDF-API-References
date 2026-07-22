---
title: "System::Net::Cache::HttpRequestCacheLevel-enum"
linktitle: "HttpRequestCacheLevel"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Cache::HttpRequestCacheLevel-enum. Enumen beskriver cacheinställningar för HTTP i C++."
type: docs
weight: 400
url: /sv/cpp/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


Enumet beskriver cacheinställningar för HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Standard | 0 | Uppfyller en begäran om en resurs antingen genom att använda den cachade kopian av resursen eller genom att skicka en begäran om resursen till servern. |
| BypassCache | 1 | Tillfredsställer en begäran genom att använda servern. |
| CacheOnly | 2 | Använder alltid klientcachen för att hämta en resurs. |
| CacheIfAvailable | 3 | Uppfyller en begäran om en resurs från cachen om resursen är tillgänglig, annars skickas en begäran till servern. |
| Revalidate | 4 | Använder en lokal kopia av en resurs om klientens tidsstämpel är densamma som tidsstämpeln för resursen på servern. Annars laddas en resurs ner från en server. |
| Reload | 5 | En resurs laddas alltid ner från servern. |
| NoCacheNoStore | 6 | Tillfredsställer aldrig en begäran genom att använda resurser från cachen och cachar inte resurser. |
| CacheOrNextCacheOnly | 7 | Uppfyller en begäran om en resurs antingen från den lokala datorns cache eller från en fjärrcache på LAN. |
| Uppdatera | 8 | Uppfyller en begäran genom att använda servern eller en cache som inte är den lokala cachen. |

## Se även

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
