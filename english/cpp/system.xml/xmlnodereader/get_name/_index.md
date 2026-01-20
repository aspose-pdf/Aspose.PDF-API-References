---
title: System::Xml::XmlNodeReader::get_Name method
linktitle: get_Name
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::get_Name method. Returns the qualified name of the current node in C++.'
type: docs
weight: 1400
url: /cpp/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name method


Returns the qualified name of the current node.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### ReturnValue

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlNodeReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. |||
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
