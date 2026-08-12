---
title: "System::Net::Sockets::SocketError enum"
linktitle: "SocketError"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::SocketError enum. Enumererar socketfeltyperna i C++."
type: docs
weight: 1300
url: /sv/cpp/system.net.sockets/socketerror/
---
## SocketError enum


Enumererar socketfeltyperna.

```cpp
enum class SocketError
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Success | 0 | En socketoperation slutfördes framgångsrikt. |
| SocketError | -1 | Ett ospecificerat socketfel inträffade. |
| Interrupted | 10004 | Ett blockerande socketanrop avbröts. |
| AccessDenied | 10013 | Åtkomst till en socket nekas. |
| Fel | 10014 | En ogiltig pekaradress har upptäckts. |
| InvalidArgument | 10022 | Ett ogiltigt argument har angivits. |
| TooManyOpenSockets | 10024 | Det finns för många öppna sockets i den underliggande socket-leverantören. |
| WouldBlock | 10035 | En operation kan inte slutföras omedelbart på en icke‑blockerande socket. |
| InProgress | 10036 | En blockerande operation pågår. |
| AlreadyInProgress | 10037 | En icke‑blockerande socket har redan en pågående operation. |
| NotSocket | 10038 | Ett försök att anropa en socket‑operation på en icke‑socket. |
| DestinationAddressRequired | 10039 | En nödvändig adress har utelämnats från en socket‑operation. |
| MessageSize | 10040 | Ett datagram är för långt. |
| ProtocolType | 10041 | En protokolltyp stöds inte av den här socketen. |
| ProtocolOption | 10042 | Ett okänt, ogiltigt eller ej stödt alternativ eller nivå används. |
| ProtocolNotSupported | 10043 | Ett protokoll är inte implementerat eller konfigurerat. |
| SocketNotSupported | 10044 | En adressfamilj stöder inte den angivna socketen. |
| OperationNotSupported | 10045 | En protokollfamilj stöder inte en adressfamilj. |
| ProtocolFamilyNotSupported | 10046 | En protokollfamilj är inte implementerad eller konfigurerad. |
| AddressFamilyNotSupported | 10047 | Den angivna adressfamiljen stöds inte. |
| AddressAlreadyInUse | 10048 | En adress kan bara användas en gång. |
| AddressNotAvailable | 10049 | Den valda IP-adressen är inte giltig i detta sammanhang. |
| NetworkDown | 10050 | Nätverket är inte tillgängligt. |
| NetworkUnreachable | 10051 | Ingen rutt till fjärrvärden finns. |
| NetworkReset | 10052 | Ett program försökte sätta 'Keep-Alive' på en anslutning som redan har gått ut. |
| ConnectionAborted | 10053 | En anslutning avbryts. |
| ConnectionReset | 10054 | En anslutning återställs av en fjärrnod. |
| NoBufferSpaceAvailable | 10055 | Ingen ledig buffertplats är tillgänglig för en socket‑operation. |
| IsConnected | 10056 | En socket är redan ansluten. |
| NotConnected | 10057 | Ett program försökte skicka eller ta emot data, och en socket är inte ansluten. |
| Shutdown | 10058 | En begäran om att skicka eller ta emot data är förbjuden eftersom socketen redan har stängts. |
| TimedOut | 10060 | Ett anslutningsförsök gick ut på tid, eller så har en ansluten värd misslyckats med att svara. |
| ConnectionRefused | 10061 | En fjärrvärd vägrar aktivt en anslutning. |
| HostDown | 10064 | En operation misslyckades eftersom en fjärrvärd är nere. |
| HostUnreachable | 10065 | Ingen nätverksrutt till den angivna värden finns. |
| ProcessLimit | 10067 | För många processer använder den underliggande socket-leverantören. |
| SystemNotReady | 10091 | Ett nätverkssubsystem är otillgängligt. |
| VersionNotSupported | 10092 | En version av den underliggande socket-leverantören är utanför intervallet. |
| NotInitialized | 10093 | Den underliggande socket-leverantören är inte initierad. |
| Kopplar ner | 10101 | En kontrollerad avstängning pågår. |
| TypeNotFound | 10109 | Den angivna klassen hittades inte. |
| HostNotFound | 11001 | Den angivna värden är okänd. |
| Försök igen | 11002 | Ett namn på en värd kan inte lösas upp. |
| NoRecovery | 11003 | Ett fel är oåterställbart eller den begärda databasen kan inte hittas. |
| NoData | 11004 | Ett begärt namn eller IP-adress hittas inte på namnservern. |

## Se även

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
