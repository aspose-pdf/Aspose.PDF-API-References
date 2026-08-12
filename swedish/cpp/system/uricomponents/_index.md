---
title: "System::UriComponents‑enum"
linktitle: "UriComponents"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::UriComponents‑enum. Representerar URI-komponenter i C++."
type: docs
weight: 9200
url: /sv/cpp/system/uricomponents/
---
## UriComponents enum


Representerar URI-komponenter.

```cpp
enum class UriComponents
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Schema | 1 | Schemadatan. |
| UserInfo | 2 | UserInfo‑data. |
| Host | 4 | Host‑data. |
| Port | 8 | Port‑data. |
| SchemeAndServer | n/a | Schemadatan, Host‑data och Port‑data. |
| Path | 16 | LocalPath‑data. |
| Fråga | 32 | Query‑data. |
| PathAndQuery | n/a | Den LocalPath och Query data. |
| HttpRequestUrl | n/a | Schemat, Värden, Porten, Query och LocalPath data. |
| Fragment | 64 | Fragment data. |
| AbsoluteUri | n/a | Schemat, Värden, Porten, Quer, LocalPath och Fragment data. |
| StrongPort | 128 | Port data; om port data inte finns i [Uri](../uri/) och en standardport har tilldelats Schemat, returneras standardporten; om det inte finns någon standardport, -1 returneras. |
| HostAndPort | n/a | Värd och Port data; om port data inte finns i [Uri](../uri/) och en standardport har tilldelats Schemat, returneras standardporten. Om det inte finns någon standardport, -1 returneras. |
| StrongAuthority | n/a | UserInfo, Värd och Port data. Om ingen port data finns i [Uri](../uri/) och en standardport har tilldelats Schemat, returneras standardporten. Om det inte finns någon standardport, -1 returneras. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Anger att avgränsaren ska inkluderas. |
| SerializationInfoString | n/a | Den kompletta [Uri](../uri/) kontexten som behövs för [Uri](../uri/) Serializers. Kontexten inkluderar IPv6 scope. |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
