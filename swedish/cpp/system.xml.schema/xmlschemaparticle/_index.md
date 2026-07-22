---
title: "System::Xml::Schema::XmlSchemaParticle-klass"
linktitle: "XmlSchemaParticle"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaParticle-klass. En basklass som är basklass för alla partikeltyper (t.ex. XmlSchemaAny) i C++."
type: docs
weight: 5400
url: /sv/cpp/system.xml.schema/xmlschemaparticle/
---
## XmlSchemaParticle class


En basklass som är basklass för alla partikeltyper (t.ex. [XmlSchemaAny](../xmlschemaany/)).

```cpp
class XmlSchemaParticle : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_MaxOccurs](./get_maxoccurs/)() | Returnerar det maximala antalet gånger partikeln kan förekomma. |
| [get_MaxOccursString](./get_maxoccursstring/)() | Returnerar talet som ett strängvärde. Maximalt antal gånger partikeln kan förekomma. |
| [get_MinOccurs](./get_minoccurs/)() | Returnerar det minsta antalet gånger partikeln kan förekomma. |
| [get_MinOccursString](./get_minoccursstring/)() | Returnerar talet som ett strängvärde. Det minsta antalet gånger partikeln kan förekomma. |
| [set_MaxOccurs](./set_maxoccurs/)(Decimal) | Ställer in det maximala antalet gånger partikeln kan förekomma. |
| [set_MaxOccursString](./set_maxoccursstring/)(const String\&) | Ställer in talet som ett strängvärde. Maximalt antal gånger partikeln kan förekomma. |
| [set_MinOccurs](./set_minoccurs/)(Decimal) | Ställer in det minsta antalet gånger partikeln kan förekomma. |
| [set_MinOccursString](./set_minoccursstring/)(const String\&) | Ställer in talet som ett strängvärde. Det minsta antalet gånger partikeln kan förekomma. |
| [XmlSchemaParticle](./xmlschemaparticle/)() | Initierar en ny instans av klassen [XmlSchemaParticle](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
