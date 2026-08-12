---
title: "System::Net::WebExceptionStatus enum"
linktitle: "WebExceptionStatus"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebExceptionStatus enum. Enumererar statuskoderna för WebException-klassen i C++."
type: docs
weight: 4900
url: /sv/cpp/system.net/webexceptionstatus/
---
## WebExceptionStatus enum


Enumererar statuskoderna för [WebException](../webexception/)-klassen.

```cpp
enum class WebExceptionStatus
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Success | 0 | Inga fel inträffade. |
| NameResolutionFailure | 1 | Tjänsten för namnupplösning kunde inte lösa värdnamnet. |
| ConnectFailure | 2 | Den fjärranslutna tjänstepunkten kunde inte nås på transportnivå. |
| ReceiveFailure | 3 | Ingen fullständig svar mottogs från den fjärranslutna servern. |
| SendFailure | 4 | En fullständig begäran kunde inte skickas till den fjärranslutna servern. |
| PipelineFailure | 5 | Begäran var en pipelined request och anslutningen stängdes innan svaret mottogs. |
| RequestCanceled | 6 | Begäran avbröts eller ett oklassificerbart fel inträffade. |
| ProtocolError | 7 | Svaret som mottogs från servern var komplett men indikerade ett fel på protokollnivå. |
| ConnectionClosed | 8 | Anslutningen stängdes för tidigt. |
| TrustFailure | 9 | Ett servercertifikat kunde inte valideras. |
| SecureChannelFailure | 10 | Ett fel inträffade när en anslutning etablerades med SSL. |
| ServerProtocolViolation | 11 | Serverns svar var inte ett giltigt HTTP-svar. |
| KeepAliveFailure | 12 | Anslutningen för en begäran som specificerar 'Keep-Alive'-headern stängdes oväntat. |
| Pending | 13 | An internal asynchronous request is pending. |
| Tidsgräns | 14 | Inget svar mottogs under tidsgränsen för en begäran. |
| ProxyNameResolutionFailure | 15 | Namntjänsten kunde inte lösa proxyvärdens namn. |
| UnknownError | 16 | Ett undantag av okänd typ har inträffat. |
| MessageLengthLimitExceeded | 17 | Ett meddelande som överskred den angivna gränsen mottogs. |
| CacheEntryNotFound | 18 | Den angivna cacheposten hittades inte. |
| RequestProhibitedByCachePolicy | 19 | Begäran tilläts inte av cachepolicyn. |
| RequestProhibitedByProxy | 20 | Denna begäran tilläts inte av proxyn. |

## Se även

* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
