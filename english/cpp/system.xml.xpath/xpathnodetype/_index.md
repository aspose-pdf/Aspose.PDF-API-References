---
title: System::Xml::XPath::XPathNodeType enum
linktitle: XPathNodeType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNodeType enum. Defines the XPath node types that can be returned from the XPathNavigator class in C++.'
type: docs
weight: 1100
url: /cpp/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum


Defines the [XPath](../) node types that can be returned from the [XPathNavigator](../xpathnavigator/) class.

```cpp
enum class XPathNodeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Root | 0 | The root node of the XML document or node tree. |
| Element | 1 | An element, such as **<element>**. |
| Attribute | 2 | An attribute, such as **id='123'**. |
| Namespace | 3 | A namespace, such as **xmlns="namespace"**. |
| Text | 4 | The text content of a node. Equivalent to the Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) and CDATA node types. Contains at least one character. |
| SignificantWhitespace | 5 | A node with white space characters and **xml:space** set to **preserve**. |
| Whitespace | 6 | A node with only white space characters and no significant white space. White space characters are **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | A processing instruction, such as **<?pi test?>**. This does not include XML declarations, which are not visible to the [XPathNavigator](../xpathnavigator/) class. |
| Comment | 8 | A comment, such as ****. |
| All | 9 | Any of the [XPathNodeType](./) node types. |

## See Also

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
