---
title: "System::Xml::XmlTextReader-klass"
linktitle: "XmlTextReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader-klass. Representerar en läsare som ger snabb, icke-cachad, framåtriktad åtkomst till XML-data i C++."
type: docs
weight: 3900
url: /sv/cpp/system.xml/xmltextreader/
---
## XmlTextReader class


Representerar en läsare som ger snabb, icke‑cachad, framåtriktad åtkomst till XML‑data.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Ändrar [XmlReader::get_ReadState](../xmlreader/get_readstate/) till **Closed**. |
| [get_AttributeCount](./get_attributecount/)() override | Returnerar antalet attribut på den aktuella noden. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar bas‑URI:n för den aktuella noden. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returnerar ett värde som indikerar om [XmlTextReader](./) implementerar metoderna för binär innehållsläsning. |
| [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Returnerar ett värde som indikerar om [XmlTextReader](./) implementerar metoden [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Returnerar ett värde som indikerar om denna läsare kan tolka och lösa upp entiteter. |
| [get_Depth](./get_depth/)() override | Returnerar djupet för den aktuella noden i XML‑dokumentet. |
| [get_DtdProcessing](./get_dtdprocessing/)() | Returnerar uppräkningen [DtdProcessing](../dtdprocessing/). |
| [get_Encoding](./get_encoding/)() | Returnerar dokumentets kodning. |
| [get_EntityHandling](./get_entityhandling/)() | Returnerar ett värde som specificerar hur läsaren hanterar entiteter. |
| [get_EOF](./get_eof/)() override | Returnerar ett värde som indikerar om läsaren är placerad i slutet av strömmen. |
| [get_HasValue](./get_hasvalue/)() override | Returnerar ett värde som indikerar om den aktuella noden kan ha ett [XmlTextReader::get_Value](./get_value/) annat än [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett attribut som genererades från standardvärdet som definierats i DTD eller schema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett tomt element (till exempel **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Returnerar det aktuella radnumret. |
| [get_LinePosition](./get_lineposition/)() override | Returnerar den aktuella radpositionen. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på den aktuella noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på den aktuella noden. |
| [get_Namespaces](./get_namespaces/)() | Returnerar ett värde som indikerar om namnrymdsstöd ska användas. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar namnrymdens URI (enligt W3C:s namnrymdsspecifikation) för den nod som läsaren är placerad på. |
| [get_NameTable](./get_nametable/)() override | Returnerar [XmlNameTable](../xmlnametable/)-objektet som är associerat med denna implementation. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_Normalization](./get_normalization/)() | Returnerar ett värde som indikerar om blanksteg och attributvärden ska normaliseras. |
| [get_Prefix](./get_prefix/)() override | Returnerar namnrymdsprefixet som är associerat med den aktuella noden. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Returnerar ett värde som indikerar om DTD-behandling ska tillåtas. |
| [get_QuoteChar](./get_quotechar/)() override | Returnerar tecknet för citattecken som används för att omge värdet för en attributnod. |
| [get_ReadState](./get_readstate/)() override | Returnerar läsarens tillstånd. |
| [get_Value](./get_value/)() override | Returnerar textvärdet för den aktuella noden. |
| [get_WhitespaceHandling](./get_whitespacehandling/)() | Returnerar ett värde som anger hur blanksteg hanteras. |
| [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [get_XmlSpace](./get_xmlspace/)() override | Returnerar det aktuella **xml:space**-omfånget. |
| [GetAttribute](./getattribute/)(String) override | Returnerar värdet på attributet med det angivna namnet. |
| [GetAttribute](./getattribute/)(String, String) override | Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI. |
| [GetAttribute](./getattribute/)(int32_t) override | Returnerar värdet på attributet med det angivna indexet. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Returnerar en samling som innehåller alla namnrymder som för närvarande är i räckvidd. |
| [GetRemainder](./getremainder/)() | Returnerar återstoden av den buffrade XML‑en. |
| [HasLineInfo](./haslineinfo/)() override | Returnerar ett värde som indikerar om klassen kan returnera radinformation. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Löser upp ett namnrymdsprefix i det aktuella elementets omfång. |
| [MoveToAttribute](./movetoattribute/)(String) override | Flyttar till attributet med det angivna namnet. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Flyttar till attributet med det angivna lokala namnet och namnrymdens URI. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Flyttar till attributet med det angivna indexet. |
| [MoveToElement](./movetoelement/)() override | Flyttar till elementet som innehåller den aktuella attributnoden. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Flyttar till det första attributet. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Flyttar till nästa attribut. |
| [Read](./read/)() override | Läser nästa nod från strömmen. |
| [ReadAttributeValue](./readattributevalue/)() override | Analyserar attributvärdet till en eller flera **[Text](../../system.text/)**, **EntityReference** eller **EndEntity** noder. |
| [ReadBase64](./readbase64/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Avkodar Base64 och returnerar de avkodade binära byten. |
| [ReadBinHex](./readbinhex/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Avkodar **BinHex** och returnerar de avkodade binära byten. |
| [ReadChars](./readchars/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) | Läser textinnehållet i ett element till en teckenbuffert. Denna metod är avsedd att läsa stora strömmar av inbäddad text genom att anropa den successivt. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser innehållet och returnerar de **Base64**‑avkodade binära byten. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser innehållet och returnerar de **BinHex**‑avkodade binära byten. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser elementet och avkodar Base64-innehållet. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Läser elementet och avkodar **BinHex**‑innehållet. |
| [ReadString](./readstring/)() override | Läser innehållet i ett element eller en textnod som en sträng. |
| [ResetState](./resetstate/)() | Återställer läsarens tillstånd till [ReadState::Initial](../readstate/). |
| [ResolveEntity](./resolveentity/)() override | Löser upp enhetsreferensen för **EntityReference**-noder. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Ställer in [DtdProcessing](../dtdprocessing/)-enumerationen. |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Ställer in ett värde som anger hur läsaren hanterar enheter. |
| [set_Namespaces](./set_namespaces/)(bool) | Ställer in ett värde som indikerar om namnrymdsstöd ska användas. |
| [set_Normalization](./set_normalization/)(bool) | Ställer in ett värde som indikerar om blanksteg och attributvärden ska normaliseras. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Ställer in ett värde som indikerar om DTD‑behandling ska tillåtas. |
| [set_WhitespaceHandling](./set_whitespacehandling/)(System::Xml::WhitespaceHandling) | Ställer in ett värde som anger hur blanksteg hanteras. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Ställer in [XmlResolver](../xmlresolver/) som används för att lösa DTD‑referenser. |
| [Skip](./skip/)() override | Hoppar över barnen till den aktuella noden. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strömmen. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en och strömmen. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strömmen och [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en, strömmen och [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna TextReader. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en och TextReader. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna TextReader och [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en, TextReader och [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strömmen, [XmlNodeType](../xmlnodetype/), och [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strängen, [XmlNodeType](../xmlnodetype/), och [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna filen. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna filen och [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Det rekommenderas att använda klassen [XmlReader](../xmlreader/) istället.

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
