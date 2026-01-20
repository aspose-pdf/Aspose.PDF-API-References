---
title: System::Xml::XmlTextReader::get_Name method
linktitle: get_Name
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::get_Name method. Returns the qualified name of the current node in C++.'
type: docs
weight: 1900
url: /cpp/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name method


Returns the qualified name of the current node.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### ReturnValue

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlTextReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. |||
|-|-|
|Node Type |Name |
|Attribute|The name of the attribute. |
|DocumentType|The document type name. |
|Element|The tag name. |
|EntityReference|The name of the entity referenced. |
|ProcessingInstruction|The target of the processing instruction. |
|XmlDeclaration|The literal string xml. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
