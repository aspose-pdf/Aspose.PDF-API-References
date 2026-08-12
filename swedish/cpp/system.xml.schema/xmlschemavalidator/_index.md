---
title: "System::Xml::Schema::XmlSchemaValidator klass"
linktitle: "XmlSchemaValidator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaValidator klass. Representerar en XML Schema Definition Language (XSD) schema valideringsmotor. XmlSchemaValidator-klassen kan inte ärvas i C++."
type: docs
weight: 7000
url: /sv/cpp/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator class


Representerar en XML [Schema](../) Definition Language (XSD) [Schema](../) valideringsmotor. Klassen [XmlSchemaValidator](./) kan inte ärvas.

```cpp
class XmlSchemaValidator : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddSchema](./addschema/)(const SharedPtr\<XmlSchema\>\&) | Lägger till ett XML [Schema](../) Definition Language (XSD) schema till mängden scheman som används för validering. |
| [EndValidation](./endvalidation/)() | Avslutar validering och kontrollerar identitetsrestriktioner för hela XML-dokumentet. |
| [get_LineInfoProvider](./get_lineinfoprovider/)() | Returnerar radnummerinformationen för den XML-nod som valideras. |
| [get_SourceUri](./get_sourceuri/)() | Returnerar käll-URI:n för den XML-nod som valideras. |
| [get_ValidationEventSender](./get_validationeventsender/)() | Returnerar objektet som skickas som avsändarobjekt för ett valideringsevent. |
| [GetExpectedAttributes](./getexpectedattributes/)() | Returnerar de förväntade attributen för det aktuella elementkontextet. |
| [GetExpectedParticles](./getexpectedparticles/)() | Returnerar de förväntade partiklarna i det aktuella elementkontextet. |
| [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) | Validerar identitetsrestriktioner på standardattributen och fyller i den angivna Listan med [XmlSchemaAttribute](../xmlschemaattribute/)‑objekt för alla attribut med standardvärden som inte tidigare har validerats med metoden [XmlSchemaValidator::ValidateAttribute](./validateattribute/) i elementkontexten. |
| [Initialize](./initialize/)() | Initierar tillståndet för objektet [XmlSchemaValidator](./). |
| [Initialize](./initialize/)(const SharedPtr\<XmlSchemaObject\>\&) | Initierar tillståndet för objektet [XmlSchemaValidator](./) med hjälp av den angivna [XmlSchemaObject](../xmlschemaobject/) för partiell validering. |
| [set_LineInfoProvider](./set_lineinfoprovider/)(const SharedPtr\<IXmlLineInfo\>\&) | Ställer in radnummerinformationen för XML‑noden som valideras. |
| [set_SourceUri](./set_sourceuri/)(const SharedPtr\<Uri\>\&) | Ställer in käll‑URI för XML‑noden som valideras. |
| [set_ValidationEventSender](./set_validationeventsender/)(const SharedPtr\<Object\>\&) | Ställer in objektet som skickas som avsändarobjekt för ett valideringsevent. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Ställer in [XmlResolver](../../system.xml/xmlresolver/)‑objektet som används för att lösa **xs:import** och **xs:include** element samt **xsi:schemaLocation** och **xsi:noNamespaceSchemaLocation** attribut. |
| [SkipToEndElement](./skiptoendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Hoppar över validering av det aktuella elementets innehåll och förbereder [XmlSchemaValidator](./)‑objektet för att validera innehåll i det överordnade elementets sammanhang. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) | Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Validerar elementet i det aktuella sammanhanget. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) | Validerar elementet i det aktuella sammanhanget med de angivna attributvärdena **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** och **xsi:NoNamespaceSchemaLocation**. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Verifierar om elementets textinnehåll är giltigt enligt dess datatyp för element med enkelt innehåll, och verifierar om innehållet i det aktuella elementet är komplett för element med komplext innehåll. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) | Verifierar om det angivna elementets textinnehåll är giltigt enligt dess datatyp. |
| [ValidateEndOfAttributes](./validateendofattributes/)(const SharedPtr\<XmlSchemaInfo\>\&) | Verifierar om alla obligatoriska attribut i elementets sammanhang är närvarande och förbereder [XmlSchemaValidator](./)‑objektet för att validera elementets barninnehåll. |
| [ValidateText](./validatetext/)(const String\&) | Validerar om den angivna text **string** är tillåten i det aktuella elementets sammanhang, och samlar texten för validering om elementet har enkelt innehåll. |
| [ValidateText](./validatetext/)(XmlValueGetter) | Validerar om den text som returneras av det angivna [XmlValueGetter](../xmlvaluegetter/)‑objektet är tillåten i det aktuella elementets sammanhang, och samlar texten för validering om elementet har enkelt innehåll. |
| [ValidateWhitespace](./validatewhitespace/)(const String\&) | Validerar om det vita utrymmet i den angivna **string** är tillåtet i det aktuella elementets sammanhang, och samlar det vita utrymmet för validering om elementet har enkelt innehåll. |
| [ValidateWhitespace](./validatewhitespace/)(XmlValueGetter) | Validerar om det vita utrymmet som returneras av det angivna [XmlValueGetter](../xmlvaluegetter/)‑objektet är tillåtet i det aktuella elementets sammanhang, och samlar det vita utrymmet för validering om elementet har enkelt innehåll. |
| [XmlSchemaValidator](./xmlschemavalidator/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) | Initierar en ny instans av klassen [XmlSchemaValidator](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
