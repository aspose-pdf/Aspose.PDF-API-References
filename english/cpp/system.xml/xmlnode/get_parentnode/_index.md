---
title: System::Xml::XmlNode::get_ParentNode method
linktitle: get_ParentNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNode::get_ParentNode method. Returns the parent of this node (for nodes that can have parents) in C++.'
type: docs
weight: 2100
url: /cpp/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode method


Returns the parent of this node (for nodes that can have parents).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### ReturnValue

The [XmlNode](../) that is the parent of the current node.
## Remarks



If a node has just been created and not yet added to the tree, or if it has been removed from the tree, the parent is **nullptr**. For all other nodes, the value returned depends on the [XmlNode::get_NodeType](../get_nodetype/) of the node. The following table describes the possible return values for the **get_NodeType** method. |||
|-|-|
|NodeType |Return Value of ParentNode |
|Attribute, Document, DocumentFragment, Entity, Notation |Returns nullptr; these nodes do not have parents. |
|CDATA |Returns the element or entity reference containing the CDATA section. |
|Comment |Returns the element, entity reference, document type, or document containing the comment. |
|DocumentType |Returns the document node. |
|Element |Returns the parent node of the element. If the element is the root node in the tree, the parent is the document node. |
|EntityReference |Returns the element, attribute, or entity reference containing the entity reference. |
|ProcessingInstruction |Returns the document, element, document type, or entity reference containing the processing instruction. |
|Text|Returns the parent element, attribute, or entity reference containing the text node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
