---
title: "System::Net::ServicePointManager klass"
linktitle: "ServicePointManager"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::ServicePointManager klass. Hanterar livscykelstadierna (skapa, underhålla och ta bort) av ServicePoint‑klassens instanser. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3200
url: /sv/cpp/system.net/servicepointmanager/
---
## ServicePointManager class


Hanterar livscykelstadierna (skapa, underhålla och ta bort) av [ServicePoint](../servicepoint/) klassinstanser. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ServicePointManager : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [get_CertificatePolicy](./get_certificatepolicy/)() | Hämtar en certifikatpolicy. |
| static [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Hämtar ett värde som indikerar om certifikatet måste kontrolleras mot certifikatutfärdarens återkallningslista. |
| static [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Hämtar det maximala antalet samtidiga anslutningar som tillåts av ServicePoint‑klassinstanserna. |
| static [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Hämtar en tidsgräns i millisekunder under vilken en DNS‑upplösning anses vara giltig. |
| static [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Hämtar ett värde som indikerar om en DNS‑upplösning roterar bland de tillämpliga IP‑adresserna. |
| static [get_EncryptionPolicy](./get_encryptionpolicy/)() | Returnerar krypteringspolicyn som används av den aktuella instansen. |
| static [get_Expect100Continue](./get_expect100continue/)() | Hämtar ett värde som indikerar om ServicePoint‑klassinstanserna använder 100‑Continue‑beteendet. |
| static [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Hämtar den maximala inaktiva tiden för ServicePoint‑klassinstanserna. |
| static [get_MaxServicePoints](./get_maxservicepoints/)() | Hämtar det maximala antalet ServicePoint‑klassinstanser som kan hanteras av den aktuella instansen. |
| static [get_ReusePort](./get_reuseport/)() | Hämtar ett värde som indikerar om utgångsanslutningssocklar använder alternativet 'SO_REUSE_UNICASTPORT'. |
| static [get_SecurityProtocol](./get_securityprotocol/)() | Hämtar säkerhetsprotokolltypen som används av ServicePoint‑klassinstanserna som hanteras av den aktuella instansen. |
| static [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Hämtar återanropet som används för att validera ett servercertifikat. |
| static [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Hämtar ett värde som indikerar om ServicePoint‑klassinstanserna använder Nagle‑algoritmen. |
| static [set_CertificatePolicy](./set_certificatepolicy/)(System::SharedPtr\<ICertificatePolicy\>) | Ställer in en certifikatpolicy. |
| static [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(bool) | Ställer in ett värde som indikerar om certifikatet måste kontrolleras mot certifikatutfärdarens återkallningslista. |
| static [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(int32_t) | Ställer in det maximala antalet samtidiga anslutningar som tillåts av ServicePoint‑klassinstanserna. |
| static [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(int32_t) | Ställer in en tidsgräns i millisekunder under vilken en DNS‑upplösning anses vara giltig. |
| static [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(bool) | Ställer in ett värde som indikerar om en DNS‑upplösning roterar bland de tillämpliga IP‑adresserna. |
| static [set_Expect100Continue](./set_expect100continue/)(bool) | Ställer in ett värde som indikerar om ServicePoint‑klassinstanserna använder 100‑Continue‑beteendet. |
| static [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(int32_t) | Ställer in den maximala inaktiva tiden för ServicePoint‑klassinstanserna. |
| static [set_MaxServicePoints](./set_maxservicepoints/)(int32_t) | Ställer in det maximala antalet ServicePoint-klassinstanser som kan hanteras av den aktuella instansen. |
| static [set_ReusePort](./set_reuseport/)(bool) | Ställer in ett värde som indikerar om utgångssocketarna för anslutningarna använder alternativet 'SO_REUSE_UNICASTPORT'. |
| static [set_SecurityProtocol](./set_securityprotocol/)(SecurityProtocolType) | Ställer in den säkerhetsprotokolltyp som används av ServicePoint-klassinstanser som hanteras av den aktuella instansen. |
| static [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)(Security::RemoteCertificateValidationCallback) | Ställer in återanropet som används för att validera ett servercertifikat. |
| static [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Ställer in ett värde som indikerar om ServicePoint-klassinstanser använder Nagle-algoritmen. |
| static [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Ställer in värdet som indikerar om alternativet 'Keep-Alive' är aktiverat. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | RTTI-information. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Standardantalet beständiga anslutningar. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
