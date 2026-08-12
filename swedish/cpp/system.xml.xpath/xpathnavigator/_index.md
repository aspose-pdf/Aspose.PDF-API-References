---
title: "System::Xml::XPath::XPathNavigator class"
linktitle: "XPathNavigator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator class. Tillhandahåller en markörmodell för att navigera och redigera XML-data i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml.xpath/xpathnavigator/
---
## XPathNavigator class


Tillhandahåller en markörmodell för att navigera och redigera XML‑data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AppendChild](./appendchild/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/) objekt som används för att skapa ett eller flera nya barnnoder i slutet av listan med barnnoder för den aktuella noden. |
| virtual [AppendChild](./appendchild/)(String) | Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med den angivna XML-datasträngen. |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlReader\>) | Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med XML-innehållet i det angivna [XmlReader](../../system.xml/xmlreader/)‑objektet. |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XPathNavigator\>) | Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med noderna i den angivna [XPathNavigator](./). |
| virtual [AppendChildElement](./appendchildelement/)(String, String, String, String) | Skapar en ny barn‑elementnod i slutet av listan med barnnoder för den aktuella noden med namnrymdsprefix, lokalt namn och namnrymd‑URI som anges med det angivna värdet. |
| virtual [CheckValidity](./checkvalidity/)(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) | Verifierar att XML‑data i [XPathNavigator](./) följer den angivna XML‑[Schema](../../system.xml.schema/)-definitionsspråket (XSD)‑schemat. |
| virtual [Clone](./clone/)() | När den åsidosätts i en avledd klass skapar den ett nytt [XPathNavigator](./) placerat på samma nod som detta [XPathNavigator](./). |
| virtual [ComparePosition](./compareposition/)(SharedPtr\<XPathNavigator\>) | Jämför positionen för den aktuella [XPathNavigator](./) med positionen för den angivna [XPathNavigator](./). |
| virtual [Compile](./compile/)(String) | Kompilerar en sträng som representerar ett [XPath](../)-uttryck och returnerar ett [XPathExpression](../xpathexpression/)-objekt. |
| virtual [CreateAttribute](./createattribute/)(String, String, String, String) | Skapar en attributnod på den aktuella elementnoden med namnrymdsprefix, lokalt namn och namnrymd‑URI som anges med det angivna värdet. |
| virtual [CreateAttributes](./createattributes/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa nya attribut på det aktuella elementet. |
| [CreateNavigator](./createnavigator/)() override | Returnerar en kopia av [XPathNavigator](./). |
| virtual [DeleteRange](./deleterange/)(SharedPtr\<XPathNavigator\>) | Tar bort ett intervall av syskonnoder från den aktuella noden till den angivna noden. |
| virtual [DeleteSelf](./deleteself/)() | Tar bort den aktuella noden och dess barnnoder. |
| virtual [Evaluate](./evaluate/)(String) | Utvärderar det angivna [XPath](../)-uttrycket och returnerar det typade resultatet. |
| virtual [Evaluate](./evaluate/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Utvärderar det angivna [XPath](../)-uttrycket och returnerar det typade resultatet, med hjälp av det angivna [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix i [XPath](../)-uttrycket. |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XPathExpression\>) | Utvärderar [XPathExpression](../xpathexpression/) och returnerar det typade resultatet. |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) | Använder det medföljande sammanhanget för att utvärdera [XPathExpression](../xpathexpression/), och returnerar det typade resultatet. |
| virtual [get_BaseURI](./get_baseuri/)() | När den åsidosätts i en avledd klass hämtas bas‑URI:n för den aktuella noden. |
| virtual [get_CanEdit](./get_canedit/)() | Returnerar ett värde som indikerar om [XPathNavigator](./) kan redigera den underliggande XML‑datan. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Returnerar ett värde som indikerar om den aktuella noden har några attribut. |
| virtual [get_HasChildren](./get_haschildren/)() | Returnerar ett värde som indikerar om den aktuella noden har några barnnoder. |
| virtual [get_InnerXml](./get_innerxml/)() | Returnerar markupen som representerar barnnoderna för den aktuella noden. |
| virtual [get_IsEmptyElement](./get_isemptyelement/)() | När den åsidosätts i en avledd klass hämtas ett värde som indikerar om den aktuella noden är ett tomt element utan ett slut‑element‑tagg. |
| [get_IsNode](./get_isnode/)() override | Returnerar ett värde som indikerar om den aktuella noden representerar en [XPath](../)-nod. |
| virtual [get_LocalName](./get_localname/)() | När den åsidosätts i en avledd klass hämtas [XPathNavigator::get_Name](./get_name/) för den aktuella noden utan något namnrymdsprefix. |
| virtual [get_Name](./get_name/)() | När den åsidosätts i en avledd klass, hämtar den det kvalificerade namnet på den aktuella noden. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | När den åsidosätts i en avledd klass, hämtar den namnrymdens URI för den aktuella noden. |
| virtual [get_NameTable](./get_nametable/)() | När den åsidosätts i en avledd klass, hämtar den [XmlNameTable](../../system.xml/xmlnametable/) för [XPathNavigator](./). |
| static [get_NavigatorComparer](./get_navigatorcomparer/)() | Returnerar en [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) som används för likhetsjämförelse av [XPathNavigator](./)-objekt. |
| virtual [get_NodeType](./get_nodetype/)() | När den åsidosätts i en avledd klass, hämtar den [XPathNodeType](../xpathnodetype/) för den aktuella noden. |
| virtual [get_OuterXml](./get_outerxml/)() | Returnerar markup som representerar öppnings- och stängningstaggarna för den aktuella noden och dess barnnoder. |
| virtual [get_Prefix](./get_prefix/)() | När den åsidosätts i en avledd klass, hämtar den namnrymdsprefixet som är associerat med den aktuella noden. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Returnerar schemainformationen som har tilldelats den aktuella noden som ett resultat av schemavalidering. |
| [get_TypedValue](./get_typedvalue/)() override | Returnerar den aktuella noden som ett boxed object av den mest lämpliga typen. |
| virtual [get_UnderlyingObject](./get_underlyingobject/)() | Används av [XPathNavigator](./)-implementationer som tillhandahåller en "virtualiserad" XML‑vy över en lagring, för att ge åtkomst till underliggande objekt. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Returnerar den aktuella nodens värde som en [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returnerar den aktuella nodens värde som en [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Returnerar den aktuella nodens värde som en [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Returnerar den aktuella nodens värde som en [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Returnerar den aktuella nodens värde som en [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Returnerar typen på den aktuella noden. |
| virtual [get_XmlLang](./get_xmllang/)() | Returnerar **xml:lang**‑omfånget för den aktuella noden. |
| [get_XmlType](./get_xmltype/)() override | Returnerar XmlSchemaType‑informationen för den aktuella noden. |
| virtual [GetAttribute](./getattribute/)(String, String) | Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI. |
| virtual [GetNamespace](./getnamespace/)(String) | Returnerar värdet på namnrymdsnoden som motsvarar det angivna lokala namnet. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Returnerar de namnrymder som är i omfång för den aktuella noden. |
| virtual [InsertAfter](./insertafter/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod efter den för närvarande valda noden. |
| virtual [InsertAfter](./insertafter/)(String) | Skapar en ny syskonnod efter den för närvarande valda noden med den angivna XML‑strängen. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlReader\>) | Skapar en ny syskonnod efter den för närvarande valda noden med XML‑innehållet i det angivna [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XPathNavigator\>) | Skapar en ny syskonnod efter den för närvarande valda noden med noderna i det angivna [XPathNavigator](./)-objektet. |
| virtual [InsertBefore](./insertbefore/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod före den för närvarande valda noden. |
| virtual [InsertBefore](./insertbefore/)(String) | Skapar en ny syskonnod före den för närvarande valda noden med den angivna XML‑strängen. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlReader\>) | Skapar en ny syskonnod före den för närvarande valda noden med XML‑innehållet i det angivna [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XPathNavigator\>) | Skapar en ny syskonnod före den för närvarande valda noden med noderna i den angivna [XPathNavigator](./). |
| virtual [InsertElementAfter](./insertelementafter/)(String, String, String, String) | Skapar ett nytt syskon‑element efter den aktuella noden med det angivna namnrymdsprefixet, lokala namnet och namnrymdens URI, med det angivna värdet. |
| virtual [InsertElementBefore](./insertelementbefore/)(String, String, String, String) | Skapar ett nytt syskonelement före den aktuella noden med det angivna namespace‑prefixet, lokala namnet och den angivna namespace‑URI:n, med det angivna värdet. |
| virtual [IsDescendant](./isdescendant/)(SharedPtr\<XPathNavigator\>) | Avgör om den angivna [XPathNavigator](./) är en ättling till den aktuella [XPathNavigator](./). |
| virtual [IsSamePosition](./issameposition/)(SharedPtr\<XPathNavigator\>) | När den åsidosätts i en avledd klass avgör den om den aktuella [XPathNavigator](./) befinner sig på samma position som den angivna [XPathNavigator](./). |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Returnerar namnrymdens URI för det angivna prefixet. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Returnerar prefixet som deklarerats för den angivna namespace‑URI:n. |
| virtual [Matches](./matches/)(SharedPtr\<XPathExpression\>) | Avgör om den aktuella noden matchar det angivna [XPathExpression](../xpathexpression/). |
| virtual [Matches](./matches/)(String) | Avgör om den aktuella noden matchar det angivna [XPath](../)-uttrycket. |
| virtual [MoveTo](./moveto/)(SharedPtr\<XPathNavigator\>) | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till samma position som den angivna [XPathNavigator](./). |
| virtual [MoveToAttribute](./movetoattribute/)(String, String) | Flyttar [XPathNavigator](./) till attributet med matchande lokalt namn och namespace‑URI. |
| virtual [MoveToChild](./movetochild/)(String, String) | Flyttar [XPathNavigator](./) till barnnoden med det angivna lokala namnet och namespace‑URI:n. |
| virtual [MoveToChild](./movetochild/)(XPathNodeType) | Flyttar [XPathNavigator](./) till barnnoden av den angivna [XPathNodeType](../xpathnodetype/). |
| virtual [MoveToFirst](./movetofirst/)() | Flyttar [XPathNavigator](./) till den första syskonnoden till den aktuella noden. |
| virtual [MoveToFirstAttribute](./movetofirstattribute/)() | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till det första attributet på den aktuella noden. |
| virtual [MoveToFirstChild](./movetofirstchild/)() | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till den första barnnoden till den aktuella noden. |
| virtual [MoveToFirstNamespace](./movetofirstnamespace/)(XPathNamespaceScope) | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till den första namnrymdsnoden som matchar den angivna [XPathNamespaceScope](../xpathnamespacescope/). |
| [MoveToFirstNamespace](./movetofirstnamespace/)() | Flyttar [XPathNavigator](./) till den första namnrymdsnoden för den aktuella noden. |
| virtual [MoveToFollowing](./movetofollowing/)(String, String) | Flyttar [XPathNavigator](./) till elementet med det angivna lokala namnet och namespace‑URI:n i dokumentordning. |
| virtual [MoveToFollowing](./movetofollowing/)(String, String, SharedPtr\<XPathNavigator\>) | Flyttar [XPathNavigator](./) till elementet med det angivna lokala namnet och namespace‑URI:n, till den angivna gränsen, i dokumentordning. |
| virtual [MoveToFollowing](./movetofollowing/)(XPathNodeType) | Flyttar [XPathNavigator](./) till det efterföljande elementet av den angivna [XPathNodeType](../xpathnodetype/) i dokumentordning. |
| virtual [MoveToFollowing](./movetofollowing/)(XPathNodeType, SharedPtr\<XPathNavigator\>) | Flyttar [XPathNavigator](./) till det efterföljande elementet av den angivna [XPathNodeType](../xpathnodetype/), till den angivna gränsen, i dokumentordning. |
| virtual [MoveToId](./movetoid/)(String) | När den åsidosätts i en avledd klass flyttar den till noden som har ett attribut av typen **ID** vars värde matchar den angivna [String](../../system/string/). |
| virtual [MoveToNamespace](./movetonamespace/)(String) | Flyttar [XPathNavigator](./) till namnrymdsnoden med det angivna namespace‑prefixet. |
| virtual [MoveToNext](./movetonext/)() | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till nästa syskonnod till den aktuella noden. |
| virtual [MoveToNext](./movetonext/)(String, String) | Flyttar [XPathNavigator](./) till nästa syskonnod med det angivna lokala namnet och namespace‑URI:n. |
| virtual [MoveToNext](./movetonext/)(XPathNodeType) | Flyttar [XPathNavigator](./) till nästa syskonnod till den aktuella noden som matchar den angivna [XPathNodeType](../xpathnodetype/). |
| virtual [MoveToNextAttribute](./movetonextattribute/)() | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till nästa attribut. |
| virtual [MoveToNextNamespace](./movetonextnamespace/)(XPathNamespaceScope) | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till nästa namnrymdsnod som matchar den angivna [XPathNamespaceScope](../xpathnamespacescope/). |
| [MoveToNextNamespace](./movetonextnamespace/)() | Flyttar [XPathNavigator](./) till nästa namnrymdsnod. |
| virtual [MoveToParent](./movetoparent/)() | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till föräldranoden för den aktuella noden. |
| virtual [MoveToPrevious](./movetoprevious/)() | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till föregående syskonnod för den aktuella noden. |
| virtual [MoveToRoot](./movetoroot/)() | Flyttar [XPathNavigator](./) till rotknuten som den aktuella noden tillhör. |
| virtual [PrependChild](./prependchild/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en ny barnnod i början av listan över barnnoder för den aktuella noden. |
| virtual [PrependChild](./prependchild/)(String) | Skapar en ny barnnod i början av listan över barnnoder för den aktuella noden med den angivna XML‑strängen. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlReader\>) | Skapar en ny barnnod i början av listan över barnnoder för den aktuella noden med XML‑innehållet i det angivna [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XPathNavigator\>) | Skapar en ny barnnod i början av listan över barnnoder för den aktuella noden med noderna i det angivna [XPathNavigator](./)-objektet. |
| virtual [PrependChildElement](./prependchildelement/)(String, String, String, String) | Skapar ett nytt barn‑element i början av listan över barnnoder för den aktuella noden med det angivna namnrymdsprefixet, lokala namnet, namnrymd‑URI:n och det angivna värdet. |
| virtual [ReadSubtree](./readsubtree/)() | Returnerar ett [XmlReader](../../system.xml/xmlreader/)-objekt som innehåller den aktuella noden och dess barnnoder. |
| virtual [ReplaceRange](./replacerange/)(SharedPtr\<XPathNavigator\>) | Ersätter ett intervall av syskonnoder från den aktuella noden till den angivna noden. |
| virtual [ReplaceSelf](./replaceself/)(String) | Ersätter den aktuella noden med innehållet i den angivna strängen. |
| virtual [ReplaceSelf](./replaceself/)(SharedPtr\<XmlReader\>) | Ersätter den aktuella noden med innehållet i det angivna [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual [ReplaceSelf](./replaceself/)(SharedPtr\<XPathNavigator\>) | Ersätter den aktuella noden med innehållet i det angivna [XPathNavigator](./)-objektet. |
| virtual [Select](./select/)(String) | Väljer en noduppsättning med det angivna [XPath](../)-uttrycket. |
| virtual [Select](./select/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Väljer en noduppsättning med det angivna [XPath](../)-uttrycket och det angivna [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [Select](./select/)(SharedPtr\<XPathExpression\>) | Väljer en noduppsättning med den angivna [XPathExpression](../xpathexpression/). |
| virtual [SelectAncestors](./selectancestors/)(XPathNodeType, bool) | Väljer alla förfäder till den aktuella noden som har en matchande [XPathNodeType](../xpathnodetype/). |
| virtual [SelectAncestors](./selectancestors/)(String, String, bool) | Väljer alla förfäder till den aktuella noden som har det angivna lokala namnet och namnrymd‑URI:n. |
| virtual [SelectChildren](./selectchildren/)(XPathNodeType) | Väljer alla barnnoder till den aktuella noden som har en matchande [XPathNodeType](../xpathnodetype/). |
| virtual [SelectChildren](./selectchildren/)(String, String) | Väljer alla barnnoder till den aktuella noden som har det angivna lokala namnet och namnrymd‑URI:n. |
| virtual [SelectDescendants](./selectdescendants/)(XPathNodeType, bool) | Väljer alla nedärvda noder till den aktuella noden som har en matchande [XPathNodeType](../xpathnodetype/). |
| virtual [SelectDescendants](./selectdescendants/)(String, String, bool) | Väljer alla nedärvda noder till den aktuella noden med det angivna lokala namnet och namnrymd‑URI:n. |
| virtual [SelectSingleNode](./selectsinglenode/)(String) | Väljer en enskild nod i [XPathNavigator](./) med den angivna [XPath](../)-frågan. |
| virtual [SelectSingleNode](./selectsinglenode/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Väljer en enskild nod i [XPathNavigator](./)-objektet med den angivna [XPath](../)-frågan och med det angivna [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [SelectSingleNode](./selectsinglenode/)(SharedPtr\<XPathExpression\>) | Väljer en enskild nod i [XPathNavigator](./) med det angivna [XPathExpression](../xpathexpression/)-objektet. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Ställer in markup som representerar undernoderna för den aktuella noden. |
| virtual [set_OuterXml](./set_outerxml/)(String) | Ställer in markup som representerar öppnings- och stängningstaggarna för den aktuella noden och dess undernoder. |
| virtual [SetTypedValue](./settypedvalue/)(SharedPtr\<Object\>) | Ställer in det typade värdet för den aktuella noden. |
| virtual [SetValue](./setvalue/)(String) | Ställer in värdet för den aktuella noden. |
| [ToString](./tostring/)() const override | Returnerar textvärdet för den aktuella noden. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Returnerar den aktuella nodens värde som den angivna typen, med hjälp av det angivna [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [WriteSubtree](./writesubtree/)(SharedPtr\<XmlWriter\>) | Strömmar den aktuella noden och dess undernoder till det angivna [XmlWriter](../../system.xml/xmlwriter/)-objektet. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [XPathItem](../xpathitem/)
* Class [IXPathNavigable](../ixpathnavigable/)
* Class [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
