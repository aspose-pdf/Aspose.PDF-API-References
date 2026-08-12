---
title: "System::Xml::Resolvers::XmlPreloadedResolver‑klass"
linktitle: "XmlPreloadedResolver"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Resolvers::XmlPreloadedResolver‑klass. Representerar en klass som används för att förfylla cachen med DTD‑er eller XML‑strömmar i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver class


Representerar en klass som används för att förfylla cachen med DTD:er eller XML-strömmar.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) | Lägger till en byte‑array i [XmlPreloadedResolver](./)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Lägger till en byte‑array i [XmlPreloadedResolver](./)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) | Lägger till en Stream i [XmlPreloadedResolver](./)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const String\&) | Lägger till en sträng med förladdade data i [XmlPreloadedResolver](./)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen. |
| [get_PreloadedUris](./get_preloadeduris/)() | Returnerar en samling av förladdade URI:er. |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Mappar en URI till ett objekt som innehåller den faktiska resursen. |
| [Remove](./remove/)(const SharedPtr\<Uri\>\&) | Tar bort den data som motsvarar URI:n från [XmlPreloadedResolver](./). |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Löser den absoluta URI:n från bas- och relativa URI:er. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Ställer in de autentiseringsuppgifter som används för att autentisera den underliggande [Net::WebRequest](../../system.net/webrequest/). |
| [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) override | Bestämmer om resolvern stöder andra typer än bara Stream. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)() | Initierar en ny instans av klassen [XmlPreloadedResolver](./). |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(XmlKnownDtds) | Initierar en ny instans av klassen [XmlPreloadedResolver](./) med de angivna förladdade välkända DTD:erna. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&) | Initierar en ny instans av klassen [XmlPreloadedResolver](./) med den angivna reservresolvern. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) | Initierar en ny instans av klassen [XmlPreloadedResolver](./) med den angivna reservresolvern och förladdade välkända DTD:er. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) | Initierar en ny instans av klassen [XmlPreloadedResolver](./) med den angivna reservresolvern, förladdade välkända DTD:er och en URI-jämförare för likhet. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlResolver](../../system.xml/xmlresolver/)
* Namespace [System::Xml::Resolvers](../)
* Library [Aspose.PDF for C++](../../)
