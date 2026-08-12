---
title: "System::Xml::XmlResolver-klass"
linktitle: "XmlResolver"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlResolver-klass. Löser upp externa XML-resurser som namnges av en Uniform Resource Identifier (URI) i C++."
type: docs
weight: 3500
url: /sv/cpp/system.xml/xmlresolver/
---
## XmlResolver class


Löser upp externa XML‑resurser som namnges av en Uniform Resource Identifier (URI).

```cpp
class XmlResolver : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) | När den åsidosätts i en avledd klass, mappar en URI till ett objekt som innehåller den faktiska resursen. |
| virtual [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) | När den åsidosätts i en avledd klass, löser upp den absoluta URI:n från bas- och relativa URI:er. |
| virtual [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) | När den åsidosätts i en avledd klass, anger de autentiseringsuppgifter som används för att autentisera webbförfrågningar. |
| virtual [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) | Gör det möjligt för resolvern att returnera typer annat än Stream. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
