---
title: System::UriComponents enum
linktitle: UriComponents
second_title: Aspose.PDF for C++ API Reference
description: 'System::UriComponents enum. Represents URI components in C++.'
type: docs
weight: 8900
url: /cpp/system/uricomponents/
---
## UriComponents enum


Represents URI components.

```cpp
enum class UriComponents
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Scheme | 1 | The Scheme data. |
| UserInfo | 2 | The UserInfo data. |
| Host | 4 | The Host data. |
| Port | 8 | The Port data. |
| SchemeAndServer | n/a | The Scheme, Host and Port data. |
| Path | 16 | The LocalPath data. |
| Query | 32 | The Query data. |
| PathAndQuery | n/a | The LocalPath and Query data. |
| HttpRequestUrl | n/a | The Scheme, Host, Port, Query and LocalPath data. |
| Fragment | 64 | The Fragment data. |
| AbsoluteUri | n/a | The Scheme, Host, Port, Quer, LocalPath and Fragment data. |
| StrongPort | 128 | The Port data; if the port data not present in the [Uri](../uri/) and a default port has been assigned to the Scheme, the default port is returned; if there is no default port, -1 is returned. |
| HostAndPort | n/a | The Host and Port data; if the port data is not present in the [Uri](../uri/) and a default port has been assigned to the Scheme, the default port is returned. If there is no default port, -1 is returned. |
| StrongAuthority | n/a | The UserInfo, Host, and Port data.If no port data is in the [Uri](../uri/) and a default port has been assigned to the Scheme, the default port is returned.If there is no default port, -1 is returned. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Specifies that the delimiter should be included. |
| SerializationInfoString | n/a | The complete [Uri](../uri/) context that is needed for [Uri](../uri/) Serializers. The context includes the IPv6 scope. |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
