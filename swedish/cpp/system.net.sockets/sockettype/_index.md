---
title: "System::Net::Sockets::SocketType enum"
linktitle: "SocketType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::SocketType enum. Enumererar sockettyperna i C++."
type: docs
weight: 1800
url: /sv/cpp/system.net.sockets/sockettype/
---
## SocketType enum


Enumererar sockettyperna.

```cpp
enum class SocketType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Stream | 1 | Typen som stödjer pålitliga, tvåvägs, anslutningsbaserade byte-strömmar utan duplicering av data och utan bevarande av gränser. |
| Dgram | 2 | Typen som stödjer datagram, vilka är anslutningslösa, opålitliga meddelanden med en fast maximal längd. |
| Raw | 3 | Typen som ger åtkomst till det underliggande transportprotokollet. |
| Rdm | 4 | Typen som stödjer anslutningslösa, meddelandeorienterade, pålitligt levererade meddelanden och bevarar meddelandegränser i data. |
| Seqpacket | 5 | Typen som tillhandahåller anslutningsorienterad och pålitlig tvåvägsöverföring av ordnade byte-strömmar över ett nätverk. |
| Okänd | n/a | En okänd typ. |

## Se även

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
