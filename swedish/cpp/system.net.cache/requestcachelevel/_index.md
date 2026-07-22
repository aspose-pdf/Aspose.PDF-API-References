---
title: "System::Net::Cache::RequestCacheLevel enum"
linktitle: "RequestCacheLevel"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Cache::RequestCacheLevel enum. Enumet beskriver cacheinställningar som gäller för alla WebRequest i C++."
type: docs
weight: 500
url: /sv/cpp/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum


Enumet beskriver cacheinställningar som gäller för alla [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Standard | 0 | Uppfyller en begäran om en resurs antingen genom att använda den cachade kopian av resursen eller genom att skicka en begäran om resursen till servern. |
| BypassCache | 1 | Uppfyller en begäran genom att använda servern. Inga poster tas från cachen. |
| CacheOnly | 2 | Uppfyller en begäran om en resurs endast från cachen. [WebException](../../system.net/webexception/) kommer att kastas när en resurs inte finns i klientcachen. |
| CacheIfAvailable | 3 | Uppfyller en begäran om en resurs från cachen om resursen är tillgänglig, annars skickas en begäran till servern. |
| Revalidate | 4 | Använder en lokal kopia av en resurs om klientens tidsstämpel är densamma som tidsstämpeln för resursen på servern. Annars laddas en resurs ner från en server. |
| Reload | 5 | En resurs laddas alltid ner från servern. |
| NoCacheNoStore | 6 | Tillfredsställer aldrig en begäran genom att använda resurser från cachen och cachar inte resurser. |

## Se även

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
