---
title: "Перечисление System::Net::Cache::RequestCacheLevel"
linktitle: "RequestCacheLevel"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Net::Cache::RequestCacheLevel. Перечисление описывает параметры кэша, применимые к любому WebRequest в C++."
type: docs
weight: 500
url: /ru/cpp/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum


Перечисление описывает параметры кэша, применимые к любому [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | 0 | Удовлетворяет запрос на ресурс, используя либо кэшированную копию ресурса, либо отправляя запрос на ресурс к серверу. |
| BypassCache | 1 | Удовлетворяет запрос, используя сервер. Записи из кэша не берутся. |
| CacheOnly | 2 | Удовлетворяет запрос на ресурс только из кэша. [WebException](../../system.net/webexception/) будет выброшено, когда ресурс отсутствует в кэше клиента. |
| CacheIfAvailable | 3 | Удовлетворяет запрос на ресурс из кэша, если ресурс доступен, иначе отправляет запрос к серверу. |
| Revalidate | 4 | Используется локальная копия ресурса, если метка времени клиента совпадает с меткой времени ресурса на сервере. В противном случае ресурс загружается с сервера. |
| Reload | 5 | Ресурс всегда загружается с сервера. |
| NoCacheNoStore | 6 | Никогда не удовлетворяет запрос, используя ресурсы из кэша, и не кэширует ресурсы. |

## См. также

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
