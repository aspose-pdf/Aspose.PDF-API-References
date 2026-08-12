---
title: "System::Net::ServicePoint klass"
linktitle: "ServicePoint"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::ServicePoint klass. Tillhandahåller HTTP-anslutningshantering. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3100
url: /sv/cpp/system.net/servicepoint/
---
## ServicePoint class


Tillhandahåller HTTP-anslutningshantering. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ServicePoint : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloseConnectionGroup](./closeconnectiongroup/)(String) | Stänger och tar bort anslutningar som tillhör den angivna anslutningsgruppen. |
| [get_Address](./get_address/)() | Returnerar server-URI:n som den aktuella instansen ansluter till. |
| [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | RTTI-information. |
| [get_Certificate](./get_certificate/)() | Returnerar ett certifikat som används av den aktuella instansen. |
| [get_ClientCertificate](./get_clientcertificate/)() | Returnerar det senaste klientcertifikatet. |
| [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Hämtar en timeout i millisekunder efter vilken aktiv [ServicePoint](./) kommer att stängas. |
| [get_ConnectionLimit](./get_connectionlimit/)() | Hämtar det maximala antalet anslutningar som den aktuella instansen tillåter. |
| [get_ConnectionName](./get_connectionname/)() | Returnerar anslutningsnamnet. |
| [get_CurrentConnections](./get_currentconnections/)() | Returnerar antalet öppna anslutningar. |
| [get_Expect100Continue](./get_expect100continue/)() | Hämtar ett värde som indikerar om 100-Continue‑beteendet används. |
| [get_IdleSince](./get_idlesince/)() | Returnerar datum och tid för den senaste anslutningen till en värd. |
| [get_MaxIdleTime](./get_maxidletime/)() | Hämtar en tidsmängd i millisekunder efter vilken en overksam anslutning kommer att stängas. |
| virtual [get_ProtocolVersion](./get_protocolversion/)() | Returnerar HTTP‑versionen. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Hämtar storleken på mottagningsbufferten. |
| [get_SupportsPipelining](./get_supportspipelining/)() | Returnerar ett värde som indikerar om den aktuella instansen stödjer pipeline‑anslutningar. |
| [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Hämtar ett värde som indikerar om Nagle‑algoritmen används av anslutningar som hanteras av den aktuella instansen. |
| [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)(BindIPEndPoint) | Ställer in delegaten som används för att associera den lokala [IPEndPoint](../ipendpoint/) med den aktuella instansen. |
| [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(int32_t) | Ställer in en tidsgräns i millisekunder efter vilken aktiva [ServicePoint](./) kommer att stängas. |
| [set_ConnectionLimit](./set_connectionlimit/)(int32_t) | Ställer in det maximala antalet anslutningar som den aktuella instansen tillåter. |
| [set_Expect100Continue](./set_expect100continue/)(bool) | Ställer in ett värde som indikerar om 100-Continue‑beteendet används. |
| [set_MaxIdleTime](./set_maxidletime/)(int32_t) | Ställer in en tidsmängd i millisekunder efter vilken en overksam anslutning kommer att stängas. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Ställer in storleken på mottagningsbufferten. |
| [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Ställer in ett värde som indikerar om Nagle‑algoritmen används av anslutningar som hanteras av den aktuella instansen. |
| [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Ställer in värdet som indikerar om alternativet 'Keep-Alive' är aktiverat. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
