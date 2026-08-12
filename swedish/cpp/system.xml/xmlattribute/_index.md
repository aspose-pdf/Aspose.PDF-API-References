---
title: "System::Xml::XmlAttribute-klass"
linktitle: "XmlAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttribute-klass. Representerar ett attribut. Giltiga och standardvärden för attributet definieras i en dokumenttypdefinition (DTD) eller ett schema i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml/xmlattribute/
---
## XmlAttribute class


Representerar ett attribut. Giltiga och standardvärden för attributet definieras i en dokumenttypdefinition (DTD) eller ett schema.

```cpp
class XmlAttribute : public System::Xml::XmlNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) override | Lägger till den angivna noden i slutet av listan med barnnoder för denna nod. |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar nodens grundläggande Uniform Resource Identifier (URI). |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar namnrymdens URI för denna nod. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returnerar [XmlDocument](../xmldocument/) som denna nod tillhör. |
| virtual [get_OwnerElement](./get_ownerelement/)() | Returnerar [XmlElement](../xmlelement/) som attributet tillhör. |
| [get_Prefix](./get_prefix/)() override | Returnerar namnrymdsprefixet för den här noden. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returnerar post-schema-validation-infoset som har tilldelats denna nod som ett resultat av schemavalidering. |
| virtual [get_Specified](./get_specified/)() | Returnerar ett värde som indikerar om attributvärdet sattes explicit. |
| [get_Value](./get_value/)() override | Returnerar värdet på noden. |
| [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Infogar den angivna noden omedelbart efter den angivna referensnoden. |
| [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Infogar den angivna noden omedelbart före den angivna referensnoden. |
| [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) override | Lägger till den angivna noden i början av listan över barnnoder för denna nod. |
| [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) override | Tar bort den angivna barnnoden. |
| [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Ersätter den angivna barnnoden med den nya angivna barnnoden. |
| [set_InnerText](./set_innertext/)(String) override | Ställer in de sammanslagna värdena för noden och alla dess barn. |
| [set_InnerXml](./set_innerxml/)(String) override | Ställer in värdet för attributet. |
| [set_Prefix](./set_prefix/)(String) override | Ställer in namnrymdsprefixet för denna nod. |
| [set_Value](./set_value/)(String) override | Ställer in värdet på noden. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den specificerade [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar noden till den specificerade [XmlWriter](../xmlwriter/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
