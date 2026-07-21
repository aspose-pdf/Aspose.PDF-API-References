---
title: "System::Net::Cache::HttpRequestCacheLevel enumeración"
linktitle: "HttpRequestCacheLevel"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Cache::HttpRequestCacheLevel enumeración. La enumeración describe la configuración de caché para HTTP en C++."
type: docs
weight: 400
url: /es/cpp/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


La enumeración describe la configuración de caché para HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Predeterminado | 0 | Satisface una solicitud de un recurso ya sea usando la copia en caché del recurso o enviando una solicitud del recurso al servidor. |
| BypassCache | 1 | Satisface una solicitud utilizando el servidor. |
| CacheOnly | 2 | Siempre usa la caché del cliente para obtener un recurso. |
| CacheIfAvailable | 3 | Satisface una solicitud de un recurso desde la caché si el recurso está disponible; de lo contrario, envía una solicitud al servidor. |
| Revalidate | 4 | Usa una copia local del recurso si la marca de tiempo del cliente es la misma que la marca de tiempo del recurso en el servidor. De lo contrario, el recurso se descarga de un servidor. |
| Reload | 5 | Un recurso siempre se descarga del servidor. |
| NoCacheNoStore | 6 | Nunca satisface una solicitud utilizando recursos del caché y no almacena recursos en caché. |
| CacheOrNextCacheOnly | 7 | Satisface una solicitud de un recurso ya sea desde la caché del equipo local o desde una caché remota en la LAN. |
| Actualizar | 8 | Satisface una solicitud utilizando el servidor o una caché distinta a la caché local. |

## Ver también

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
