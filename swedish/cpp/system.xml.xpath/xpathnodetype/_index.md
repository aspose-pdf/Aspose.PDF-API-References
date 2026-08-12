---
title: "System::Xml::XPath::XPathNodeType enum"
linktitle: "XPathNodeType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNodeType enum. Definierar XPath-nodtyperna som kan returneras från XPathNavigator-klassen i C++."
type: docs
weight: 1100
url: /sv/cpp/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum


Definierar [XPath](../)-nodtyperna som kan returneras från [XPathNavigator](../xpathnavigator/)-klassen.

```cpp
enum class XPathNodeType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Rot | 0 | Rotnoden i XML-dokumentet eller nodträdet. |
| Element | 1 | Ett element, till exempel **<element>**. |
| Attribute | 2 | Ett attribut, till exempel **id='123'**. |
| Namnområde | 3 | Ett namnrymd, till exempel **xmlns=\"namespace\"**. |
| Text | 4 | Textinnehållet i en nod. Motsvarar Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) och CDATA-nodtyper. Innehåller minst ett tecken. |
| SignificantWhitespace | 5 | En nod med blankstegstecken och **xml:space** satt till **preserve**. |
| Whitespace | 6 | En nod med endast blankstegstecken och ingen betydande blanksteg. Blankstegstecken är **'\\x20'**, **'\\x0d'**, **'\\x0a'**, **'\\x09'**. |
| ProcessingInstruction | 7 | En bearbetningsinstruktion, till exempel **<?pi test?>**. Detta inkluderar inte XML-deklarationer, som inte är synliga för [XPathNavigator](../xpathnavigator/)-klassen. |
| Comment | 8 | En kommentar, till exempel ****. |
| All | 9 | Någon av [XPathNodeType](./) nodtyperna. |

## Se även

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
