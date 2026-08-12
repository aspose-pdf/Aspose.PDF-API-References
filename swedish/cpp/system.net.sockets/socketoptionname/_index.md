---
title: "System::Net::Sockets::SocketOptionName enum"
linktitle: "SocketOptionName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::SocketOptionName enum. Definierar socketalternativnamn för Socket-klassen i C++."
type: docs
weight: 1600
url: /sv/cpp/system.net.sockets/socketoptionname/
---
## SocketOptionName enum


Definierar namn på socket‑alternativ för klassen [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Felsök | 1 | Registrera felsökningsinformation. |
| AcceptConnection | 2 | Indikerar om en socket lyssnar på en inkommande anslutning. |
| ReuseAddress | 4 | Indikerar om en socket kan bindas till en adress som redan är i bruk. |
| KeepAlive | 8 | Aktiverar 'Keep-Alive'-paket för en socket‑anslutning. |
| DontRoute | 16 | Indikerar om ett paket skickas direkt till gränssnittsadresserna. |
| Broadcast | 32 | Indikerar om en socket kan skicka broadcast‑meddelanden. |
| UseLoopback | 64 | Kringgå hårdvara när det är möjligt. |
| Linger | 128 | Systemet kommer att blockera processen vid stängningsförsöket tills den kan överföra data. |
| OutOfBandInline | 256 | Tar emot out-of-band-data i den normala dataströmmen. |
| DontLinger | n/a | Indikerar om en socket kommer att stängas utan fördröjning. |
| ExclusiveAddressUse | n/a | En socket kommer att använda den bundna adressen exklusivt. |
| SendBuffer | 4097 | Anger storleken på sändningsbufferten. |
| ReceiveBuffer | 4098 | Anger storleken på mottagningsbufferten. |
| SendLowWater | 4099 | Anger den minsta mängden data för sändningsoperationerna. |
| ReceiveLowWater | 4100 | Anger den minsta mängden data för mottagningsoperationerna. |
| SendTimeout | 4101 | Anger tidsgränsen för de synkrona sändningsoperationerna. |
| ReceiveTimeout | 4102 | Anger tidsgränsen för de synkrona mottagningsoperationerna. |
| Error | 4103 | Returnerar felstatusen och rensar. |
| Typ | 4104 | Returnerar en socket-typ. |
| ReuseUnicastPort | 12295 | Indikerar om systemet ska skjuta upp den tillfälliga portallokeringen för utgående anslutningar. |
| MaxConnections | 2147483647 | Detta alternativ stöds inte. Det användes för att ange maximal kölängd för lyssning. |
| IPOptions | 1 | Anger IP‑alternativet som måste infogas i utgående datagram. |
| HeaderIncluded | 2 | Rubriken inkluderas i utgående datagram. |
| TypeOfService | 3 | Ändra IP‑huvudets typ av servicefältet. |
| IpTimeToLive | 4 | IP‑tiden för livslängd. |
| MulticastInterface | 9 | Ställ in gränssnittet för de utgående multicast‑paketen. |
| MulticastTimeToLive | 10 | IP‑multicastens tid för livslängd. |
| MulticastLoopback | 11 | IP‑multicastens loopback. |
| AddMembership | 12 | Lägg till ett IP‑gruppmedlemskap. |
| DropMembership | 13 | Ta bort ett IP‑gruppmedlemskap. |
| DontFragment | 14 | Fragmentera inte IP‑datagrammen. |
| AddSourceMembership | 15 | Gå med i IP‑grupp/källa. |
| DropSourceMembership | 16 | Ta bort IP‑grupp/källa. |
| BlockSource | 17 | Blockera IP-grupp/källan. |
| UnblockSource | 18 | Avblockera IP-grupp/källan. |
| PacketInformation | 19 | Ta emot paketinformation för IPv4. |
| HopLimit | 21 | Levererar ett heltal som innehåller HOP-antalet för paketet. |
| IPProtectionLevel | 23 | Aktiverar begränsning av en IPv6-socket till den angivna räckvidden. |
| IPv6Only | 27 | Socketen är begränsad till att endast skicka och ta emot IPv6-paket. |
| NoDelay | 1 | Inaktiverar Nagle-algoritmen för sammanslagning av sändningspaket. |
| BsdUrgent | 2 | Använd den brådskande datan enligt RFC-1222. |
| Expedited | 2 | Använd den påskyndade datan enligt RFC-1222. |
| NoChecksum | 1 | Skicka UDP-datagrammen med en kontrollsumma satt till noll. |
| ChecksumCoverage | 20 | Ställ in eller hämta UDP-kontrollsummeomfånget. |
| UpdateAcceptContext | 28683 | Uppdaterar en klient-socket med samma egenskaper som en lyssnande socket. |
| UpdateConnectContext | 28688 | Uppdaterar en klient-socket med samma egenskaper som en lyssnande socket. |

## Se även

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
