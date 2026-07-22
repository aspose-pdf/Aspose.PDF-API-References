---
title: "System::Xml::XmlValidatingReader klass"
linktitle: "XmlValidatingReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader klass. Representerar en läsare som tillhandahåller dokumenttypdefinition (DTD), XML-Data Reduced (XDR) schema och XML Schema definitionsspråk (XSD) validering i C++."
type: docs
weight: 4200
url: /sv/cpp/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader class


Representerar en läsare som tillhandahåller dokumenttypdefinition (DTD), XML-Data Reduced (XDR) schema och XML [Schema](../../system.xml.schema/) definitionsspråk (XSD) validering.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Ändrar [XmlReader::get_ReadState](../xmlreader/get_readstate/) till Stängd. |
| [get_AttributeCount](./get_attributecount/)() override | Returnerar antalet attribut på den aktuella noden. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar bas‑URI:n för den aktuella noden. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returnerar ett värde som indikerar om [XmlValidatingReader](./) implementerar metoderna för binär innehållsläsning. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Returnerar ett värde som indikerar om denna läsare kan tolka och lösa upp entiteter. |
| [get_Depth](./get_depth/)() override | Returnerar djupet för den aktuella noden i XML‑dokumentet. |
| [get_Encoding](./get_encoding/)() | Returnerar kodningsattributet för dokumentet. |
| [get_EntityHandling](./get_entityhandling/)() | Returnerar ett värde som specificerar hur läsaren hanterar entiteter. |
| [get_EOF](./get_eof/)() override | Returnerar ett värde som indikerar om läsaren är placerad i slutet av strömmen. |
| [get_HasValue](./get_hasvalue/)() override | Returnerar ett värde som indikerar om den aktuella noden kan ha ett [XmlValidatingReader::get_Value](./get_value/) annat än [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett attribut som genererats från standardvärdet som definierats i dokumenttypdefinitionen (DTD) eller schemat. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett tomt element (till exempel **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Returnerar det aktuella radnumret. |
| [get_LinePosition](./get_lineposition/)() override | Returnerar den aktuella radpositionen. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på den aktuella noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på den aktuella noden. |
| [get_Namespaces](./get_namespaces/)() | Returnerar ett värde som indikerar om namnrymdsstöd ska användas. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar nodens namnrymd Uniform Resource Identifier (URI) (enligt definitionen i World Wide [Web](../../system.web/) Consortium (W3C) Namespace-specifikationen) där läsaren är placerad. |
| [get_NameTable](./get_nametable/)() override | Returnerar [XmlNameTable](../xmlnametable/)-objektet som är associerat med denna implementation. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_Prefix](./get_prefix/)() override | Returnerar namnrymdsprefixet som är associerat med den aktuella noden. |
| [get_QuoteChar](./get_quotechar/)() override | Returnerar tecknet för citattecken som används för att omge värdet för en attributnod. |
| [get_Reader](./get_reader/)() | Returnerar den [XmlReader](../xmlreader/) som användes för att konstruera denna [XmlValidatingReader](./). |
| [get_ReadState](./get_readstate/)() override | Returnerar läsarens tillstånd. |
| [get_Schemas](./get_schemas/)() | Returnerar en XmlSchemaCollection att använda för validering. |
| [get_SchemaType](./get_schematype/)() | Returnerar ett schematypobjekt. |
| [get_ValidationType](./get_validationtype/)() | Returnerar ett värde som indikerar vilken typ av validering som ska utföras. |
| [get_Value](./get_value/)() override | Returnerar textvärdet för den aktuella noden. |
| [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [get_XmlSpace](./get_xmlspace/)() override | Returnerar det aktuella **xml:space**-omfånget. |
| [GetAttribute](./getattribute/)(String) override | Returnerar värdet på attributet med det angivna namnet. |
| [GetAttribute](./getattribute/)(String, String) override | Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI). |
| [GetAttribute](./getattribute/)(int32_t) override | Returnerar värdet på attributet med det angivna indexet. |
| [HasLineInfo](./haslineinfo/)() override | Returnerar ett värde som indikerar om klassen kan returnera radinformation. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Löser upp ett namnrymdsprefix i det aktuella elementets omfång. |
| [MoveToAttribute](./movetoattribute/)(String) override | Flyttar till attributet med det angivna namnet. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Flyttar till attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI). |
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
| [ReadTypedValue](./readtypedvalue/)() | Returnerar körtidstypen för den angivna XML [Schema](../../system.xml.schema/) definition language (XSD)-typen. |
| [ResolveEntity](./resolveentity/)() override | Löser upp enhetsreferensen för **EntityReference**-noder. |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Ställer in ett värde som anger hur läsaren hanterar enheter. |
| [set_Namespaces](./set_namespaces/)(bool) | Ställer in ett värde som indikerar om namnrymdsstöd ska användas. |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Ställer in ett värde som indikerar vilken typ av validering som ska utföras. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Ställer in den [XmlResolver](../xmlresolver/) som används för att lösa externa dokumenttypdefinitioner (DTD) och schemalokaliseringsreferenser. [XmlResolver](../xmlresolver/) används också för att hantera eventuella import- eller include-element som finns i XML [Schema](../../system.xml.schema/) definition language (XSD)-scheman. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Lägger till en händelsehanterare för att ta emot information om dokumenttypdefinition (DTD), XML-Data Reduced (XDR)-schema och XML [Schema](../../system.xml.schema/) definition language (XSD)-schemavalideringsfel. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Tar bort en händelsehanterare för att ta emot information om dokumenttypdefinition (DTD), XML-Data Reduced (XDR)-schema och XML [Schema](../../system.xml.schema/) definition language (XSD)-schemavalideringsfel. |
| [XmlValidatingReader](./xmlvalidatingreader/)(const SharedPtr\<XmlReader\>\&) | Initierar en ny instans av klassen [XmlValidatingReader](./) som validerar innehållet som returneras från den angivna [XmlReader](../xmlreader/). |
| [XmlValidatingReader](./xmlvalidatingreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initierar en ny instans av klassen [XmlValidatingReader](./) med de angivna värdena. |
| [XmlValidatingReader](./xmlvalidatingreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initierar en ny instans av klassen [XmlValidatingReader](./) med de angivna värdena. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar


## Deprecated
Denna klass är föråldrad. Det rekommenderas att använda klassen XmlReaderSettings och metoden XmlReader::Create för att skapa en validerande XML-läsare.

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
