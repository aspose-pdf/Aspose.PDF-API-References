---
title: "System::Xml::XmlSecureResolver-klass"
linktitle: "XmlSecureResolver"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlSecureResolver-klass. Hjälper till att säkra en annan implementation av XmlResolver genom att omsluta XmlResolver-objektet och begränsa de resurser som den underliggande XmlResolver har åtkomst till i C++."
type: docs
weight: 3600
url: /sv/cpp/system.xml/xmlsecureresolver/
---
## XmlSecureResolver class


Hjälper till att säkra en annan implementation av [XmlResolver](../xmlresolver/) genom att omsluta [XmlResolver](../xmlresolver/) objekt och begränsa de resurser som den underliggande [XmlResolver](../xmlresolver/) har åtkomst till.

```cpp
class XmlSecureResolver : public System::Xml::XmlResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Mappar en URI till ett objekt som innehåller den faktiska resursen. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Löser den absoluta URI:n från bas- och relativa URI:er genom att anropa **ResolveUri** på den underliggande [XmlResolver](../xmlresolver/). |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Ställer in autentiseringsuppgifter som används för att autentisera webbförfrågningar. |
| [XmlSecureResolver](./xmlsecureresolver/)(const SharedPtr\<XmlResolver\>\&, const String\&) | Initierar en ny instans av klassen [XmlSecureResolver](./) med den angivna [XmlResolver](../xmlresolver/) och URL:en. |
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
