---
title: System::Xml::XmlReader::get_Name method
linktitle: get_Name
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::get_Name method. When overridden in a derived class, gets the qualified name of the current node in C++.'
type: docs
weight: 1500
url: /cpp/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name method


When overridden in a derived class, gets the qualified name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### ReturnValue

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. |||
|-|-|
|Node type |Name |
|Attribute|The name of the attribute. |
|DocumentType|The document type name. |
|Element|The tag name. |
|EntityReference|The name of the entity referenced. |
|ProcessingInstruction|The target of the processing instruction. |
|XmlDeclaration|The literal string xml. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
