---
title: System::Xml::XmlNode class
linktitle: XmlNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNode class. Represents a single node in the XML document in C++.'
type: docs
weight: 2500
url: /cpp/system.xml/xmlnode/
---
## XmlNode class


Represents a single node in the XML document.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) | Adds the specified node to the end of the list of child nodes, of this node. |
| virtual [Clone](./clone/)() | Creates a duplicate of this node. |
| virtual [CloneNode](./clonenode/)(bool) | Creates a duplicate of the node, when overridden in a derived class. |
| [CreateNavigator](./createnavigator/)() override | Creates an XPathNavigator for navigating this object. |
| virtual [get_Attributes](./get_attributes/)() | Returns an [XmlAttributeCollection](../xmlattributecollection/) containing the attributes of this node. |
| virtual [get_BaseURI](./get_baseuri/)() | Returns the base URI of the current node. |
| virtual [get_ChildNodes](./get_childnodes/)() | Returns all the child nodes of the node. |
| virtual [get_FirstChild](./get_firstchild/)() | Returns the first child of the node. |
| virtual [get_HasChildNodes](./get_haschildnodes/)() | Returns a value indicating whether this node has any child nodes. |
| virtual [get_InnerText](./get_innertext/)() | Returns the concatenated values of the node and all its child nodes. |
| virtual [get_InnerXml](./get_innerxml/)() | Returns the markup representing only the child nodes of this node. |
| virtual [get_IsReadOnly](./get_isreadonly/)() | Returns a value indicating whether the node is read-only. |
| virtual [get_LastChild](./get_lastchild/)() | Returns the last child of the node. |
| virtual [get_LocalName](./get_localname/)() | Returns the local name of the node, when overridden in a derived class. |
| virtual [get_Name](./get_name/)() | Returns the qualified name of the node, when overridden in a derived class. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | Returns the namespace URI of this node. |
| virtual [get_NextSibling](./get_nextsibling/)() | Returns the node immediately following this node. |
| virtual [get_NodeType](./get_nodetype/)() | Returns the type of the current node, when overridden in a derived class. |
| virtual [get_OuterXml](./get_outerxml/)() | Returns the markup containing this node and all its child nodes. |
| virtual [get_OwnerDocument](./get_ownerdocument/)() | Returns the [XmlDocument](../xmldocument/) to which this node belongs. |
| virtual [get_ParentNode](./get_parentnode/)() | Returns the parent of this node (for nodes that can have parents). |
| virtual [get_Prefix](./get_prefix/)() | Returns the namespace prefix of this node. |
| virtual [get_PreviousSibling](./get_previoussibling/)() | Returns the node immediately preceding this node. |
| virtual [get_PreviousText](./get_previoustext/)() | Returns the text node that immediately precedes this node. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Returns the post schema validation infoset that has been assigned to this node as a result of schema validation. |
| virtual [get_Value](./get_value/)() | Returns the value of the node. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the child nodes in the current node. |
| virtual [GetNamespaceOfPrefix](./getnamespaceofprefix/)(String) | Looks up the closest **xmlns** declaration for the given prefix that is in scope for the current node and returns the namespace URI in the declaration. |
| virtual [GetPrefixOfNamespace](./getprefixofnamespace/)(String) | Looks up the closest **xmlns** declaration for the given namespace URI that is in scope for the current node and returns the prefix defined in that declaration. |
| virtual [idx_get](./idx_get/)(String) | Returns the first child element with the specified [XmlNode::get_Name](./get_name/). |
| virtual [idx_get](./idx_get/)(String, String) | Returns the first child element with the specified [XmlNode::get_LocalName](./get_localname/) and [XmlNode::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Inserts the specified node immediately after the specified reference node. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Inserts the specified node immediately before the specified reference node. |
| virtual [Normalize](./normalize/)() | Puts all [XmlText](../xmltext/) nodes in the full depth of the sub-tree underneath this [XmlNode](./) into a "normal" form where only markup (that is, tags, comments, processing instructions, CDATA sections, and entity references) separates [XmlText](../xmltext/) nodes, that is, there are no adjacent [XmlText](../xmltext/) nodes. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) | Adds the specified node to the beginning of the list of child nodes for this node. |
| virtual [RemoveAll](./removeall/)() | Removes all the child nodes and/or attributes of the current node. |
| virtual [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) | Removes specified child node. |
| virtual [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Replaces the child node **oldChild** with **newChild** node. |
| [SelectNodes](./selectnodes/)(const String\&) | Selects a list of nodes matching the [XPath](../../system.xml.xpath/) expression. |
| [SelectNodes](./selectnodes/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Selects a list of nodes matching the [XPath](../../system.xml.xpath/) expression. Any prefixes found in the [XPath](../../system.xml.xpath/) expression are resolved using the supplied [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SelectSingleNode](./selectsinglenode/)(const String\&) | Selects the first [XmlNode](./) that matches the [XPath](../../system.xml.xpath/) expression. |
| [SelectSingleNode](./selectsinglenode/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Selects the first [XmlNode](./) that matches the [XPath](../../system.xml.xpath/) expression. Any prefixes found in the [XPath](../../system.xml.xpath/) expression are resolved using the supplied [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual [set_InnerText](./set_innertext/)(String) | Sets the concatenated values of the node and all its child nodes. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Sets the markup representing only the child nodes of this node. |
| virtual [set_Prefix](./set_prefix/)(String) | Sets the namespace prefix of this node. |
| virtual [set_Value](./set_value/)(String) | Sets the value of the node. |
| virtual [Supports](./supports/)(String, String) | Tests if the DOM implementation implements a specific feature. |
| virtual [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) | Saves all the child nodes of the node to the specified [XmlWriter](../xmlwriter/), when overridden in a derived class. |
| virtual [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) | Saves the current node to the specified [XmlWriter](../xmlwriter/), when overridden in a derived class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
