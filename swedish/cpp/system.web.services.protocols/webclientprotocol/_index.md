---
title: "System::Web::Services::Protocols::WebClientProtocol-klass"
linktitle: "WebClientProtocol"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::WebClientProtocol-klass. Denna basklass används i alla XML Web‑tjänste‑klientproxyer som skapats med ASP.NET. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.web.services.protocols/webclientprotocol/
---
## WebClientProtocol class


Denna basklass används i alla XML [Web](../../system.web/) tjänste‑klientproxyer som skapats med ASP.NET. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class WebClientProtocol : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Abort](./abort/)() | Avbryter begäran. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() | Hämtar namnet på anslutningsgruppen. |
| [get_Credentials](./get_credentials/)() | Hämtar autentiseringsinformationen. |
| [get_PreAuthenticate](./get_preauthenticate/)() | Hämtar ett värde som indikerar om förautentisering är aktiverad. |
| [get_RequestEncoding](./get_requestencoding/)() | Hämtar kodningen som används för att göra klientförfrågningarna. |
| [get_Timeout](./get_timeout/)() | Hämtar tidsintervallet att vänta innan begäran får timeout. |
| [get_Uri](./get_uri/)() | Hämtar XML [Web](../../system.web/) tjänstens URI. |
| [get_Url](./get_url/)() | Hämtar XML [Web](../../system.web/) tjänstens URL. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Hämtar ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(String) | Ställer in namnet på anslutningsgruppen. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<Net::ICredentials\>) | Ställer in autentiseringsinformationen. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) | Anger ett värde som indikerar om förautentisering är aktiverad. |
| [set_RequestEncoding](./set_requestencoding/)(System::SharedPtr\<Text::Encoding\>) | Anger kodningen som används för att göra klientförfrågningarna. |
| [set_Timeout](./set_timeout/)(int32_t) | Ställer in tidsintervallet att vänta innan begäran får timeout. |
| [set_Uri](./set_uri/)(System::SharedPtr\<Uri\>) | Anger XML [Web](../../system.web/) tjänstens URI. |
| [set_Url](./set_url/)(String) | Anger XML [Web](../../system.web/) tjänstens URL. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Ställer in ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
