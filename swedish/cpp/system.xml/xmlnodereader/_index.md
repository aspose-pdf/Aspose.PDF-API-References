---
title: "System::Xml::XmlNodeReader-klass"
linktitle: "XmlNodeReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader-klass. Representerar en läsare som ger snabb, icke‑cachad framåtriktad åtkomst till XML‑data i en XmlNode i C++."
type: docs
weight: 2800
url: /sv/cpp/system.xml/xmlnodereader/
---
## XmlNodeReader class


Representerar en läsare som ger snabb, icke‑cachad framåtriktad åtkomst till XML‑data i en [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Ändrar [XmlNodeReader::get_ReadState](./get_readstate/) till [ReadState::Closed](../readstate/). |
| [get_AttributeCount](./get_attributecount/)() override | Returnerar antalet attribut på den aktuella noden. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar bas‑URI:n för den aktuella noden. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returnerar ett värde som indikerar om [XmlNodeReader](./) implementerar metoderna för binär innehållsläsning. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Returnerar ett värde som indikerar om denna läsare kan tolka och lösa upp entiteter. |
| [get_Depth](./get_depth/)() override | Returnerar djupet för den aktuella noden i XML‑dokumentet. |
| [get_EOF](./get_eof/)() override | Returnerar ett värde som indikerar om läsaren är placerad i slutet av strömmen. |
| [get_HasAttributes](./get_hasattributes/)() override | Returnerar ett värde som indikerar om den aktuella noden har några attribut. |
| [get_HasValue](./get_hasvalue/)() override | Returnerar ett värde som indikerar om den aktuella noden kan ha ett [XmlNodeReader::get_Value](./get_value/)-värde. |
| [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett attribut som genererats från standardvärdet som definierats i dokumenttypdefinitionen (DTD) eller schemat. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett tomt element (till exempel **<MyElement/>**). |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på den aktuella noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på den aktuella noden. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar namnrymdens URI (enligt W3C:s namnrymdsspecifikation) för den nod som läsaren är placerad på. |
| [get_NameTable](./get_nametable/)() override | Returnerar [XmlNameTable](../xmlnametable/)-objektet som är associerat med denna implementation. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_Prefix](./get_prefix/)() override | Returnerar namnrymdsprefixet som är associerat med den aktuella noden. |
| [get_ReadState](./get_readstate/)() override | Returnerar läsarens tillstånd. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returnerar schemainformationen som har tilldelats den aktuella noden. |
| [get_Value](./get_value/)() override | Returnerar textvärdet för den aktuella noden. |
| [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [get_XmlSpace](./get_xmlspace/)() override | Returnerar det aktuella **xml:space**-omfånget. |
| [GetAttribute](./getattribute/)(String) override | Returnerar värdet på attributet med det angivna namnet. |
| [GetAttribute](./getattribute/)(String, String) override | Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI. |
| [GetAttribute](./getattribute/)(int32_t) override | Returnerar värdet på attributet med det angivna indexet. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Löser upp ett namnrymdsprefix i det aktuella elementets omfång. |
| [MoveToAttribute](./movetoattribute/)(String) override | Flyttar till attributet med det angivna namnet. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Flyttar till attributet med det angivna lokala namnet och namnrymdens URI. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Flyttar till attributet med det angivna indexet. |
| [MoveToElement](./movetoelement/)() override | Flyttar till elementet som innehåller den aktuella attributnoden. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Flyttar till det första attributet. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Flyttar till nästa attribut. |
| [Read](./read/)() override | Läser nästa nod från strömmen. |
| [ReadAttributeValue](./readattributevalue/)() override | Analyserar attributvärdet till en eller flera **[Text](../../system.text/)**, **EntityReference** eller **EndEntity** noder. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser innehållet och returnerar de Base64-avkodade binära byten. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser innehållet och returnerar de BinHex-avkodade binära byten. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser elementet och avkodar Base64-innehållet. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser elementet och avkodar BinHex-innehållet. |
| [ReadString](./readstring/)() override | Läser innehållet i ett element eller en textnod som en sträng. |
| [ResolveEntity](./resolveentity/)() override | Löser upp enhetsreferensen för **EntityReference**-noder. |
| [Skip](./skip/)() override | Hoppar över barnen till den aktuella noden. |
| [XmlNodeReader](./xmlnodereader/)(const SharedPtr\<XmlNode\>\&) | Skapar en instans av klassen [XmlNodeReader](./) med den angivna [XmlNode](../xmlnode/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlReader](../xmlreader/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
