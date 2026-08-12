---
title: "System::Net::Cache::HttpCacheAgeControl enumeración"
linktitle: "HttpCacheAgeControl"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración System::Net::Cache::HttpCacheAgeControl. CacheAgeControl se utiliza para especificar preferencias respecto a la edad y frescura de los elementos en caché en C++."
type: docs
weight: 300
url: /es/cpp/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl se usa para especificar preferencias respecto a la edad y frescura de los elementos en caché.

```cpp
enum class HttpCacheAgeControl
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Solo para uso interno. |
| MinFresh | 1 | El contenido puede obtenerse de la caché si el tiempo restante antes de la expiración es mayor o igual al tiempo especificado con este valor. |
| MaxAge | 2 | El contenido puede obtenerse de la caché hasta que sea más antiguo que la edad especificada con este valor. |
| MaxStale | 4 | El contenido puede obtenerse de la caché después de que haya expirado hasta que transcurra el tiempo especificado con este valor. |
| MaxAgeAndMinFresh | 3 | MaxAge y MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge y MaxStale. |

## Ver también

* Namespace [System::Net::Cache](../)
* Library [Aspose.PDF for C++](../../)
