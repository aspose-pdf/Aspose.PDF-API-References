---
title: "System::Xml::XmlNode-klass"
linktitle: "XmlNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode-klass. Representerar en enskild nod i XML-dokumentet i C++."
type: docs
weight: 2500
url: /sv/cpp/system.xml/xmlnode/
---
## XmlNode class


Representerar en enskild nod i XML-dokumentet.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) | Lägger till den angivna noden i slutet av listan med barnnoder för denna nod. |
| virtual [Clone](./clone/)() | Skapar en duplikat av denna nod. |
| virtual [CloneNode](./clonenode/)(bool) | Skapar en duplikat av noden när den åsidosätts i en avledd klass. |
| [CreateNavigator](./createnavigator/)() override | Skapar en XPathNavigator för att navigera detta objekt. |
| virtual [get_Attributes](./get_attributes/)() | Returnerar en [XmlAttributeCollection](../xmlattributecollection/) som innehåller attributen för denna nod. |
| virtual [get_BaseURI](./get_baseuri/)() | Returnerar bas‑URI:n för den aktuella noden. |
| virtual [get_ChildNodes](./get_childnodes/)() | Returnerar alla barnnoder för noden. |
| virtual [get_FirstChild](./get_firstchild/)() | Returnerar den första barnet för noden. |
| virtual [get_HasChildNodes](./get_haschildnodes/)() | Returnerar ett värde som indikerar om denna nod har några barnnoder. |
| virtual [get_InnerText](./get_innertext/)() | Returnerar de sammanslagna värdena för noden och alla dess barnnoder. |
| virtual [get_InnerXml](./get_innerxml/)() | Returnerar markup som endast representerar barnnoderna för denna nod. |
| virtual [get_IsReadOnly](./get_isreadonly/)() | Returnerar ett värde som indikerar om noden är skrivskyddad. |
| virtual [get_LastChild](./get_lastchild/)() | Returnerar det sista barnet för noden. |
| virtual [get_LocalName](./get_localname/)() | Returnerar det lokala namnet på noden när den åsidosätts i en avledd klass. |
| virtual [get_Name](./get_name/)() | Returnerar det kvalificerade namnet på noden när den åsidosätts i en avledd klass. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | Returnerar namnrymdens URI för denna nod. |
| virtual [get_NextSibling](./get_nextsibling/)() | Returnerar noden som omedelbart följer denna nod. |
| virtual [get_NodeType](./get_nodetype/)() | Returnerar typen av den aktuella noden när den åsidosätts i en avledd klass. |
| virtual [get_OuterXml](./get_outerxml/)() | Returnerar markup som innehåller denna nod och alla dess barnnoder. |
| virtual [get_OwnerDocument](./get_ownerdocument/)() | Returnerar [XmlDocument](../xmldocument/) som denna nod tillhör. |
| virtual [get_ParentNode](./get_parentnode/)() | Returnerar föräldern till denna nod (för noder som kan ha föräldrar). |
| virtual [get_Prefix](./get_prefix/)() | Returnerar namnrymdsprefixet för den här noden. |
| virtual [get_PreviousSibling](./get_previoussibling/)() | Returnerar noden som omedelbart föregår denna nod. |
| virtual [get_PreviousText](./get_previoustext/)() | Returnerar textnoden som omedelbart föregår denna nod. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Returnerar post‑schemavaliderings‑infosettet som har tilldelats den här noden som ett resultat av schemavalidering. |
| virtual [get_Value](./get_value/)() | Returnerar värdet på noden. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom barnnoderna i den aktuella noden. |
| virtual [GetNamespaceOfPrefix](./getnamespaceofprefix/)(String) | Söker upp den närmaste **xmlns**-deklarationen för det angivna prefixet som är i räckhåll för den aktuella noden och returnerar namnrymdens URI i deklarationen. |
| virtual [GetPrefixOfNamespace](./getprefixofnamespace/)(String) | Söker upp den närmaste **xmlns**-deklarationen för den angivna namnrymdens URI som är i räckhåll för den aktuella noden och returnerar prefixet som definieras i den deklarationen. |
| virtual [idx_get](./idx_get/)(String) | Returnerar det första barnelementet med den angivna [XmlNode::get_Name](./get_name/). |
| virtual [idx_get](./idx_get/)(String, String) | Returnerar det första barnelementet med de angivna [XmlNode::get_LocalName](./get_localname/) och [XmlNode::get_NamespaceURI](./get_namespaceuri/) värdena. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Infogar den angivna noden omedelbart efter den angivna referensnoden. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Infogar den angivna noden omedelbart före den angivna referensnoden. |
| virtual [Normalize](./normalize/)() | Placera alla [XmlText](../xmltext/) noder i hela djupet av delträdet under denna [XmlNode](./) i ett "normalt" format där endast markup (det vill säga taggar, kommentarer, processinstruktioner, CDATA‑sektioner och entitetsreferenser) separerar [XmlText](../xmltext/) noder, det vill säga att det inte finns några intilliggande [XmlText](../xmltext/) noder. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) | Lägger till den angivna noden i början av listan över barnnoder för denna nod. |
| virtual [RemoveAll](./removeall/)() | Tar bort alla barnnoder och/eller attribut för den aktuella noden. |
| virtual [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) | Tar bort angiven barnnod. |
| virtual [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Ersätter barnnoden **oldChild** med **newChild**-noden. |
| [SelectNodes](./selectnodes/)(const String\&) | Väljer en lista med noder som matchar [XPath](../../system.xml.xpath/)-uttrycket. |
| [SelectNodes](./selectnodes/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Väljer en lista med noder som matchar [XPath](../../system.xml.xpath/)-uttrycket. Eventuella prefix som finns i [XPath](../../system.xml.xpath/)-uttrycket löses upp med den medföljande [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SelectSingleNode](./selectsinglenode/)(const String\&) | Väljer den första [XmlNode](./) som matchar [XPath](../../system.xml.xpath/)-uttrycket. |
| [SelectSingleNode](./selectsinglenode/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Väljer den första [XmlNode](./) som matchar [XPath](../../system.xml.xpath/)-uttrycket. Eventuella prefix som finns i [XPath](../../system.xml.xpath/)-uttrycket löses upp med den medföljande [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual [set_InnerText](./set_innertext/)(String) | Ställer in de sammanslagna värdena för noden och alla dess barnnoder. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Ställer in markup som endast representerar barnnoderna för denna nod. |
| virtual [set_Prefix](./set_prefix/)(String) | Ställer in namnrymdsprefixet för denna nod. |
| virtual [set_Value](./set_value/)(String) | Ställer in värdet på noden. |
| virtual [Supports](./supports/)(String, String) | Testar om DOM‑implementeringen implementerar en specifik funktion. |
| virtual [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) | Sparar alla barnnoder för noden till den angivna [XmlWriter](../xmlwriter/), när den åsidosätts i en avledd klass. |
| virtual [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) | Sparar den aktuella noden till den angivna [XmlWriter](../xmlwriter/), när den åsidosätts i en avledd klass. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
