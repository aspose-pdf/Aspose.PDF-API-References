---
title: "System::Xml::XmlDocument-klass"
linktitle: "XmlDocument"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument-klass. Representerar ett XML‑dokument. Du kan använda denna klass för att läsa in, validera, redigera, lägga till och placera XML i ett dokument i C++."
type: docs
weight: 1400
url: /sv/cpp/system.xml/xmldocument/
---
## XmlDocument class


Representerar ett XML-dokument. Du kan använda den här klassen för att läsa in, validera, redigera, lägga till och positionera XML i ett dokument.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [CreateAttribute](./createattribute/)(const String\&) | Skapar ett [XmlAttribute](../xmlattribute/) med det angivna namnet. |
| [CreateAttribute](./createattribute/)(const String\&, const String\&) | Skapar ett [XmlAttribute](../xmlattribute/) med det angivna kvalificerade namnet och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateAttribute](./createattribute/)(const String\&, const String\&, const String\&) | Skapar ett [XmlAttribute](../xmlattribute/) med den angivna [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateCDataSection](./createcdatasection/)(const String\&) | Skapar en [XmlCDataSection](../xmlcdatasection/) som innehåller de angivna data. |
| virtual [CreateComment](./createcomment/)(const String\&) | Skapar en [XmlComment](../xmlcomment/) som innehåller de angivna data. |
| virtual [CreateDocumentFragment](./createdocumentfragment/)() | Skapar ett [XmlDocumentFragment](../xmldocumentfragment/). |
| virtual [CreateDocumentType](./createdocumenttype/)(const String\&, const String\&, const String\&, const String\&) | Returnerar ett nytt [XmlDocumentType](../xmldocumenttype/) objekt. |
| [CreateElement](./createelement/)(const String\&) | Skapar ett element med det angivna namnet. |
| [CreateElement](./createelement/)(const String\&, const String\&) | Skapar ett [XmlElement](../xmlelement/) med det kvalificerade namnet och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateElement](./createelement/)(const String\&, const String\&, const String\&) | Skapar ett element med den angivna [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateEntityReference](./createentityreference/)(const String\&) | Skapar en [XmlEntityReference](../xmlentityreference/) med det angivna namnet. |
| [CreateNavigator](./createnavigator/)() override | Skapar ett nytt XPathNavigator-objekt för att navigera i detta dokument. |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&, const String\&) | Skapar ett [XmlNode](../xmlnode/) med den angivna [XmlNodeType](../xmlnodetype/), [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_Name](./get_name/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(const String\&, const String\&, const String\&) | Skapar ett [XmlNode](../xmlnode/) med den angivna nodtypen, [XmlDocument::get_Name](./get_name/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&) | Skapar ett [XmlNode](../xmlnode/) med den angivna [XmlNodeType](../xmlnodetype/), [XmlDocument::get_Name](./get_name/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateProcessingInstruction](./createprocessinginstruction/)(const String\&, const String\&) | Skapar en [XmlProcessingInstruction](../xmlprocessinginstruction/) med det angivna namnet och data. |
| virtual [CreateSignificantWhitespace](./createsignificantwhitespace/)(const String\&) | Skapar en [XmlSignificantWhitespace](../xmlsignificantwhitespace/) nod. |
| virtual [CreateTextNode](./createtextnode/)(const String\&) | Skapar ett [XmlText](../xmltext/) med den angivna texten. |
| virtual [CreateWhitespace](./createwhitespace/)(const String\&) | Skapar en [XmlWhitespace](../xmlwhitespace/) nod. |
| virtual [CreateXmlDeclaration](./createxmldeclaration/)(const String\&, const String\&, const String\&) | Skapar en [XmlDeclaration](../xmldeclaration/) nod med de angivna värdena. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar bas‑URI:n för den aktuella noden. |
| [get_DocumentElement](./get_documentelement/)() | Returnerar rot-[XmlElement](../xmlelement/) för dokumentet. |
| virtual [get_DocumentType](./get_documenttype/)() | Returnerar noden som innehåller DOCTYPE-deklarationen. |
| [get_Implementation](./get_implementation/)() | Returnerar [XmlImplementation](../xmlimplementation/)-objektet för det aktuella dokumentet. |
| [get_InnerXml](./get_innerxml/)() override | Returnerar markup som representerar barnen till den aktuella noden. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returnerar ett värde som indikerar om den aktuella noden är skrivskyddad. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NameTable](./get_nametable/)() | Returnerar [XmlNameTable](../xmlnametable/)-objektet som är associerat med denna implementation. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returnerar [XmlDocument](./) som den aktuella noden tillhör. |
| [get_PreserveWhitespace](./get_preservewhitespace/)() | Returnerar ett värde som anger om blanksteg ska bevaras i elementinnehåll. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returnerar nodens Post-Schema-Validation-Infoset (PSVI). |
| [get_Schemas](./get_schemas/)() | Returnerar XmlSchemaSet-objektet som är associerat med detta [XmlDocument](./). |
| virtual [GetElementById](./getelementbyid/)(String) | Returnerar [XmlElement](../xmlelement/) med det angivna ID-t. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Returnerar en [XmlNodeList](../xmlnodelist/) som innehåller en lista över alla underordnade element som matchar det angivna namnet. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Returnerar en [XmlNodeList](../xmlnodelist/) som innehåller en lista över alla underordnade element som matchar det angivna [XmlDocument::get_LocalName](./get_localname/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [ImportNode](./importnode/)(SharedPtr\<XmlNode\>, bool) | Importerar en nod från ett annat dokument till det aktuella dokumentet. |
| virtual [Load](./load/)(String) | Läser in XML-dokumentet från den angivna URL:en. |
| virtual [Load](./load/)(SharedPtr\<IO::Stream\>) | Läser in XML-dokumentet från den angivna strömmen. |
| virtual [Load](./load/)(SharedPtr\<IO::TextReader\>) | Läser in XML-dokumentet från den angivna TextReader. |
| virtual [Load](./load/)(SharedPtr\<XmlReader\>) | Läser in XML-dokumentet från den angivna [XmlReader](../xmlreader/). |
| virtual [LoadXml](./loadxml/)(String) | Läser in XML-dokumentet från den angivna strängen. |
| virtual [ReadNode](./readnode/)(SharedPtr\<XmlReader\>) | Skapar ett [XmlNode](../xmlnode/)‑objekt baserat på informationen i [XmlReader](../xmlreader/). Läsaren måste vara placerad på en nod eller ett attribut. |
| virtual [Save](./save/)(String) | Sparar XML-dokumentet till den angivna filen. Om den angivna filen finns, skriver den här metoden över den. |
| virtual [Save](./save/)(SharedPtr\<IO::Stream\>) | Sparar XML-dokumentet till den angivna strömmen. |
| virtual [Save](./save/)(SharedPtr\<IO::TextWriter\>) | Sparar XML-dokumentet till den angivna TextWriter. |
| virtual [Save](./save/)(SharedPtr\<XmlWriter\>) | Sparar XML-dokumentet till den angivna [XmlWriter](../xmlwriter/). |
| [set_InnerText](./set_innertext/)(String) override | Kastar ett InvalidOperationException i alla fall. |
| [set_InnerXml](./set_innerxml/)(String) override | Ställer in markup som representerar barnen till den aktuella noden. |
| [set_PreserveWhitespace](./set_preservewhitespace/)(bool) | Ställer in ett värde som anger om blanksteg ska bevaras i elementinnehåll. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Ställer in XmlSchemaSet‑objektet som är associerat med detta [XmlDocument](./). |
| virtual [set_XmlResolver](./set_xmlresolver/)(SharedPtr\<System::Xml::XmlResolver\>) | Ställer in [XmlResolver](../xmlresolver/) som ska användas för att lösa externa resurser. |
| [Validate](./validate/)(Schema::ValidationEventHandler) | Validerar [XmlDocument](./) mot XML [Schema](../../system.xml.schema/) Definition Language (XSD)-scheman som finns i listan [XmlDocument::get_Schemas](./get_schemas/). |
| [Validate](./validate/)(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) | Validerar det angivna [XmlNode](../xmlnode/)-objektet mot XML [Schema](../../system.xml.schema/) Definition Language (XSD)-scheman i listan [XmlDocument::get_Schemas](./get_schemas/). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till [XmlDocument](./)-noden till den angivna [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar [XmlDocument](./)-noden till den angivna [XmlWriter](../xmlwriter/). |
| [XmlDocument](./xmldocument/)() | Initierar en ny instans av klassen [XmlDocument](./). |
| [XmlDocument](./xmldocument/)(const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlDocument](./) med den angivna [XmlNameTable](../xmlnametable/). |
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
