---
title: "System::UriComponents enumeración"
linktitle: "UriComponents"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::UriComponents enumeración. Representa los componentes URI en C++."
type: docs
weight: 9200
url: /es/cpp/system/uricomponents/
---
## UriComponents enum


Representa los componentes de una URI.

```cpp
enum class UriComponents
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Esquema | 1 | Los datos del esquema. |
| UserInfo | 2 | Los datos de UserInfo. |
| Host | 4 | Los datos del Host. |
| Puerto | 8 | Los datos del puerto. |
| SchemeAndServer | n/a | Los datos del esquema, Host y puerto. |
| Ruta | 16 | Los datos de LocalPath. |
| Consulta | 32 | Los datos de la consulta. |
| PathAndQuery | n/a | Los datos de LocalPath y consulta. |
| HttpRequestUrl | n/a | Los datos del esquema, Host, puerto, consulta y LocalPath. |
| Fragment | 64 | Los datos del fragmento. |
| AbsoluteUri | n/a | Los datos del esquema, Host, puerto, consulta, LocalPath y fragmento. |
| StrongPort | 128 | Los datos del puerto; si los datos del puerto no están presentes en el [Uri](../uri/) y se ha asignado un puerto predeterminado al esquema, se devuelve el puerto predeterminado; si no hay puerto predeterminado, se devuelve -1. |
| HostAndPort | n/a | Los datos del Host y del puerto; si los datos del puerto no están presentes en el [Uri](../uri/) y se ha asignado un puerto predeterminado al esquema, se devuelve el puerto predeterminado. Si no hay puerto predeterminado, se devuelve -1. |
| StrongAuthority | n/a | Los datos de UserInfo, Host y puerto. Si no hay datos del puerto en el [Uri](../uri/) y se ha asignado un puerto predeterminado al esquema, se devuelve el puerto predeterminado. Si no hay puerto predeterminado, se devuelve -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Especifica que el delimitador debe incluirse. |
| SerializationInfoString | n/a | El contexto completo del [Uri](../uri/) que se necesita para los Serializadores de [Uri](../uri/). El contexto incluye el ámbito IPv6. |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
