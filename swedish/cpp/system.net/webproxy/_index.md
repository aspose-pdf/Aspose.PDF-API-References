---
title: "System::Net::WebProxy-klass"
linktitle: "WebProxy"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebProxy-klass. Representerar en http-webproxyserver. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3700
url: /sv/cpp/system.net/webproxy/
---
## WebProxy class


Representerar en http-webproxyserver. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Address](./get_address/)() | Hämtar adressen till den aktuella proxyservern. |
| [get_BypassList](./get_bypasslist/)() | Hämtar listan över adresser som inte använder proxyservern. |
| [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Hämtar ett värde som indikerar om proxyservern måste användas för lokala adresser. |
| virtual [get_Credentials](./get_credentials/)() | Hämtar autentiseringsuppgifterna som skickas till proxyservern. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Hämtar ett värde som indikerar om standarduppgifterna måste skickas med förfrågningar. |
| static [GetDefaultProxy](./getdefaultproxy/)() | Returnerar proxyservern som använder de icke-dynamiska inställningarna i Internet Explorer. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Returnerar den proxade URI:n för en webbförfrågan. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Kontrollerar om proxyservern inte används för den angivna URI:n. |
| [set_Address](./set_address/)(System::SharedPtr\<Uri\>) | Ställer in adressen till den aktuella proxyservern. |
| [set_BypassList](./set_bypasslist/)(System::ArrayPtr\<String\>) | Ställer in listan över adresser som inte använder proxyservern. |
| [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(bool) | Ställer in ett värde som indikerar om proxyservern måste användas för lokala adresser. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Ställer in autentiseringsuppgifterna som skickas till proxyservern för autentisering. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Ställer in ett värde som indikerar om standarduppgifterna måste skickas med förfrågningar. |
| [WebProxy](./webproxy/)() | Skapar en ny instans. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(String, int32_t) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(String) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(String, bool) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>) | Skapar en ny instans. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Skapar en ny instans. |
## Se även

* Class [IWebProxy](../iwebproxy/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
