---
title: "System::Xml::Schema::XmlSchemaInfo klass"
linktitle: "XmlSchemaInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaInfo klass. Representerar post-schema-validerings‑infosettet för en validerad XML-nod i C++."
type: docs
weight: 3800
url: /sv/cpp/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo class


Representerar post-schema-validerings‑infosettet för en validerad XML‑nod.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ContentType](./get_contenttype/)() | Returnerar objektet [XmlSchemaContentType](../xmlschemacontenttype/) som motsvarar innehållstypen för denna validerade XML-nod. |
| [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om denna validerade XML-nod sattes som resultat av ett standardvärde som tillämpades under XML [Schema](../) Definition Language (XSD) schemavalidering. |
| [get_IsNil](./get_isnil/)() override | Returnerar ett värde som indikerar om värdet för denna validerade XML-nod är **nil**. |
| [get_MemberType](./get_membertype/)() override | Returnerar den dynamiska schematypen för denna validerade XML-nod. |
| [get_SchemaAttribute](./get_schemaattribute/)() override | Returnerar det kompilerade objektet [XmlSchemaAttribute](../xmlschemaattribute/) som motsvarar denna validerade XML-nod. |
| [get_SchemaElement](./get_schemaelement/)() override | Returnerar det kompilerade objektet [XmlSchemaElement](../xmlschemaelement/) som motsvarar denna validerade XML-nod. |
| [get_SchemaType](./get_schematype/)() override | Returnerar den statiska XML [Schema](../) Definition Language (XSD) schematypen för denna validerade XML-nod. |
| [get_Validity](./get_validity/)() override | Returnerar värdet [XmlSchemaValidity](../xmlschemavalidity/) för denna validerade XML-nod. |
| [set_ContentType](./set_contenttype/)(XmlSchemaContentType) | Ställer in objektet [XmlSchemaContentType](../xmlschemacontenttype/) som motsvarar innehållstypen för denna validerade XML-nod. |
| [set_IsDefault](./set_isdefault/)(bool) | Ställer in ett värde som indikerar om denna validerade XML-nod sattes som resultat av ett standardvärde som tillämpades under XML [Schema](../) Definition Language (XSD) schemavalidering. |
| [set_IsNil](./set_isnil/)(bool) | Ställer in ett värde som indikerar om värdet för denna validerade XML-nod är **nil**. |
| [set_MemberType](./set_membertype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Ställer in den dynamiska schematypen för denna validerade XML-nod. |
| [set_SchemaAttribute](./set_schemaattribute/)(const SharedPtr\<XmlSchemaAttribute\>\&) | Ställer in det kompilerade objektet [XmlSchemaAttribute](../xmlschemaattribute/) som motsvarar denna validerade XML-nod. |
| [set_SchemaElement](./set_schemaelement/)(const SharedPtr\<XmlSchemaElement\>\&) | Ställer in det kompilerade [XmlSchemaElement](../xmlschemaelement/)‑objektet som motsvarar den här validerade XML‑noden. |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Ställer in den statiska XML [Schema](../) Definition Language (XSD)-schematypen för den här validerade XML‑noden. |
| [set_Validity](./set_validity/)(XmlSchemaValidity) | Ställer in [XmlSchemaValidity](../xmlschemavalidity/)-värdet för den här validerade XML‑noden. |
| [XmlSchemaInfo](./xmlschemainfo/)() | Initierar en ny instans av klassen [XmlSchemaInfo](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [IXmlSchemaInfo](../ixmlschemainfo/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
