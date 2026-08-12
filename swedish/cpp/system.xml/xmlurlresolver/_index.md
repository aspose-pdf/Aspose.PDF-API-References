---
title: "System::Xml::XmlUrlResolver-klass"
linktitle: "XmlUrlResolver"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlUrlResolver-klass. Löser externa XML-resurser som namnges av en Uniform Resource Identifier (URI) i C++."
type: docs
weight: 4100
url: /sv/cpp/system.xml/xmlurlresolver/
---
## XmlUrlResolver class


Löser upp externa XML‑resurser som namnges av en Uniform Resource Identifier (URI).

```cpp
class XmlUrlResolver : public System::Xml::XmlResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Mappar en URI till ett objekt som innehåller den faktiska resursen. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Löser den absoluta URI:n från bas- och relativa URI:er. |
| [set_CachePolicy](./set_cachepolicy/)(const SharedPtr\<Net::Cache::RequestCachePolicy\>\&) | Ställer in cachepolicy för det underliggande WebRequest-objektet. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Ställer in autentiseringsuppgifter som används för att autentisera webbförfrågningar. |
| [set_Proxy](./set_proxy/)(const SharedPtr\<Net::IWebProxy\>\&) | Ställer in nätverksproxy för det underliggande WebRequest-objektet. |
| [XmlUrlResolver](./xmlurlresolver/)() | Initierar en ny instans av klassen [XmlUrlResolver](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlResolver](../xmlresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
