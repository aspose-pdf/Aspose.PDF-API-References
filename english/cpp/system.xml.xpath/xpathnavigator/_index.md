---
title: System::Xml::XPath::XPathNavigator class
linktitle: XPathNavigator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator class. Provides a cursor model for navigating and editing XML data in C++.'
type: docs
weight: 500
url: /cpp/system.xml.xpath/xpathnavigator/
---
## XPathNavigator class


Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AppendChild](./appendchild/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create one or more new child nodes at the end of the list of child nodes of the current node. |
| virtual [AppendChild](./appendchild/)(String) | Creates a new child node at the end of the list of child nodes of the current node using the XML data string specified. |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlReader\>) | Creates a new child node at the end of the list of child nodes of the current node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XPathNavigator\>) | Creates a new child node at the end of the list of child nodes of the current node using the nodes in the [XPathNavigator](./) specified. |
| virtual [AppendChildElement](./appendchildelement/)(String, String, String, String) | Creates a new child element node at the end of the list of child nodes of the current node using the namespace prefix, local name and namespace URI specified with the value specified. |
| virtual [CheckValidity](./checkvalidity/)(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) | Verifies that the XML data in the [XPathNavigator](./) conforms to the XML [Schema](../../system.xml.schema/) definition language (XSD) schema provided. |
| virtual [Clone](./clone/)() | When overridden in a derived class, creates a new [XPathNavigator](./) positioned at the same node as this [XPathNavigator](./). |
| virtual [ComparePosition](./compareposition/)(SharedPtr\<XPathNavigator\>) | Compares the position of the current [XPathNavigator](./) with the position of the [XPathNavigator](./) specified. |
| virtual [Compile](./compile/)(String) | Compiles a string representing an [XPath](../) expression and returns an [XPathExpression](../xpathexpression/) object. |
| virtual [CreateAttribute](./createattribute/)(String, String, String, String) | Creates an attribute node on the current element node using the namespace prefix, local name and namespace URI specified with the value specified. |
| virtual [CreateAttributes](./createattributes/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create new attributes on the current element. |
| [CreateNavigator](./createnavigator/)() override | Returns a copy of the [XPathNavigator](./). |
| virtual [DeleteRange](./deleterange/)(SharedPtr\<XPathNavigator\>) | Deletes a range of sibling nodes from the current node to the node specified. |
| virtual [DeleteSelf](./deleteself/)() | Deletes the current node and its child nodes. |
| virtual [Evaluate](./evaluate/)(String) | Evaluates the specified [XPath](../) expression and returns the typed result. |
| virtual [Evaluate](./evaluate/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Evaluates the specified [XPath](../) expression and returns the typed result, using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes in the [XPath](../) expression. |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XPathExpression\>) | Evaluates the [XPathExpression](../xpathexpression/) and returns the typed result. |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) | Uses the supplied context to evaluate the [XPathExpression](../xpathexpression/), and returns the typed result. |
| virtual [get_BaseURI](./get_baseuri/)() | When overridden in a derived class, gets the base URI for the current node. |
| virtual [get_CanEdit](./get_canedit/)() | Returns a value that indicates whether the [XPathNavigator](./) can edit the underlying XML data. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Returns a value that indicates whether the current node has any attributes. |
| virtual [get_HasChildren](./get_haschildren/)() | Returns a value that indicates whether the current node has any child nodes. |
| virtual [get_InnerXml](./get_innerxml/)() | Returns the markup representing the child nodes of the current node. |
| virtual [get_IsEmptyElement](./get_isemptyelement/)() | When overridden in a derived class, gets a value that indicates whether the current node is an empty element without an end element tag. |
| [get_IsNode](./get_isnode/)() override | Returns a value that indicates if the current node represents an [XPath](../) node. |
| virtual [get_LocalName](./get_localname/)() | When overridden in a derived class, gets the [XPathNavigator::get_Name](./get_name/) of the current node without any namespace prefix. |
| virtual [get_Name](./get_name/)() | When overridden in a derived class, gets the qualified name of the current node. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | When overridden in a derived class, gets the namespace URI of the current node. |
| virtual [get_NameTable](./get_nametable/)() | When overridden in a derived class, gets the [XmlNameTable](../../system.xml/xmlnametable/) of the [XPathNavigator](./). |
| static [get_NavigatorComparer](./get_navigatorcomparer/)() | Returns an [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) used for equality comparison of [XPathNavigator](./) objects. |
| virtual [get_NodeType](./get_nodetype/)() | When overridden in a derived class, gets the [XPathNodeType](../xpathnodetype/) of the current node. |
| virtual [get_OuterXml](./get_outerxml/)() | Returns the markup representing the opening and closing tags of the current node and its child nodes. |
| virtual [get_Prefix](./get_prefix/)() | When overridden in a derived class, gets the namespace prefix associated with the current node. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Returns the schema information that has been assigned to the current node as a result of schema validation. |
| [get_TypedValue](./get_typedvalue/)() override | Returns the current node as a boxed object of the most appropriate type. |
| virtual [get_UnderlyingObject](./get_underlyingobject/)() | Used by [XPathNavigator](./) implementations which provide a "virtualized" XML view over a store, to provide access to underlying objects. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Returns the current node's value as a [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returns the current node's value as a [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Returns the current node's value as a [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Returns the current node's value as an [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Returns the current node's value as an [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Returns the type of the current node. |
| virtual [get_XmlLang](./get_xmllang/)() | Returns the **xml:lang** scope for the current node. |
| [get_XmlType](./get_xmltype/)() override | Returns the XmlSchemaType information for the current node. |
| virtual [GetAttribute](./getattribute/)(String, String) | Returns the value of the attribute with the specified local name and namespace URI. |
| virtual [GetNamespace](./getnamespace/)(String) | Returns the value of the namespace node corresponding to the specified local name. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Returns the in-scope namespaces of the current node. |
| virtual [InsertAfter](./insertafter/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create a new sibling node after the currently selected node. |
| virtual [InsertAfter](./insertafter/)(String) | Creates a new sibling node after the currently selected node using the XML string specified. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlReader\>) | Creates a new sibling node after the currently selected node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XPathNavigator\>) | Creates a new sibling node after the currently selected node using the nodes in the [XPathNavigator](./) object specified. |
| virtual [InsertBefore](./insertbefore/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create a new sibling node before the currently selected node. |
| virtual [InsertBefore](./insertbefore/)(String) | Creates a new sibling node before the currently selected node using the XML string specified. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlReader\>) | Creates a new sibling node before the currently selected node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XPathNavigator\>) | Creates a new sibling node before the currently selected node using the nodes in the [XPathNavigator](./) specified. |
| virtual [InsertElementAfter](./insertelementafter/)(String, String, String, String) | Creates a new sibling element after the current node using the namespace prefix, local name and namespace URI specified, with the value specified. |
| virtual [InsertElementBefore](./insertelementbefore/)(String, String, String, String) | Creates a new sibling element before the current node using the namespace prefix, local name, and namespace URI specified, with the value specified. |
| virtual [IsDescendant](./isdescendant/)(SharedPtr\<XPathNavigator\>) | Determines whether the specified [XPathNavigator](./) is a descendant of the current [XPathNavigator](./). |
| virtual [IsSamePosition](./issameposition/)(SharedPtr\<XPathNavigator\>) | When overridden in a derived class, determines whether the current [XPathNavigator](./) is at the same position as the specified [XPathNavigator](./). |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Returns the namespace URI for the specified prefix. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Returns the prefix declared for the specified namespace URI. |
| virtual [Matches](./matches/)(SharedPtr\<XPathExpression\>) | Determines whether the current node matches the specified [XPathExpression](../xpathexpression/). |
| virtual [Matches](./matches/)(String) | Determines whether the current node matches the specified [XPath](../) expression. |
| virtual [MoveTo](./moveto/)(SharedPtr\<XPathNavigator\>) | When overridden in a derived class, moves the [XPathNavigator](./) to the same position as the specified [XPathNavigator](./). |
| virtual [MoveToAttribute](./movetoattribute/)(String, String) | Moves the [XPathNavigator](./) to the attribute with the matching local name and namespace URI. |
| virtual [MoveToChild](./movetochild/)(String, String) | Moves the [XPathNavigator](./) to the child node with the local name and namespace URI specified. |
| virtual [MoveToChild](./movetochild/)(XPathNodeType) | Moves the [XPathNavigator](./) to the child node of the [XPathNodeType](../xpathnodetype/) specified. |
| virtual [MoveToFirst](./movetofirst/)() | Moves the [XPathNavigator](./) to the first sibling node of the current node. |
| virtual [MoveToFirstAttribute](./movetofirstattribute/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the first attribute of the current node. |
| virtual [MoveToFirstChild](./movetofirstchild/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the first child node of the current node. |
| virtual [MoveToFirstNamespace](./movetofirstnamespace/)(XPathNamespaceScope) | When overridden in a derived class, moves the [XPathNavigator](./) to the first namespace node that matches the [XPathNamespaceScope](../xpathnamespacescope/) specified. |
| [MoveToFirstNamespace](./movetofirstnamespace/)() | Moves the [XPathNavigator](./) to first namespace node of the current node. |
| virtual [MoveToFollowing](./movetofollowing/)(String, String) | Moves the [XPathNavigator](./) to the element with the local name and namespace URI specified in document order. |
| virtual [MoveToFollowing](./movetofollowing/)(String, String, SharedPtr\<XPathNavigator\>) | Moves the [XPathNavigator](./) to the element with the local name and namespace URI specified, to the boundary specified, in document order. |
| virtual [MoveToFollowing](./movetofollowing/)(XPathNodeType) | Moves the [XPathNavigator](./) to the following element of the [XPathNodeType](../xpathnodetype/) specified in document order. |
| virtual [MoveToFollowing](./movetofollowing/)(XPathNodeType, SharedPtr\<XPathNavigator\>) | Moves the [XPathNavigator](./) to the following element of the [XPathNodeType](../xpathnodetype/) specified, to the boundary specified, in document order. |
| virtual [MoveToId](./movetoid/)(String) | When overridden in a derived class, moves to the node that has an attribute of type **ID** whose value matches the specified [String](../../system/string/). |
| virtual [MoveToNamespace](./movetonamespace/)(String) | Moves the [XPathNavigator](./) to the namespace node with the specified namespace prefix. |
| virtual [MoveToNext](./movetonext/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the next sibling node of the current node. |
| virtual [MoveToNext](./movetonext/)(String, String) | Moves the [XPathNavigator](./) to the next sibling node with the local name and namespace URI specified. |
| virtual [MoveToNext](./movetonext/)(XPathNodeType) | Moves the [XPathNavigator](./) to the next sibling node of the current node that matches the [XPathNodeType](../xpathnodetype/) specified. |
| virtual [MoveToNextAttribute](./movetonextattribute/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the next attribute. |
| virtual [MoveToNextNamespace](./movetonextnamespace/)(XPathNamespaceScope) | When overridden in a derived class, moves the [XPathNavigator](./) to the next namespace node matching the [XPathNamespaceScope](../xpathnamespacescope/) specified. |
| [MoveToNextNamespace](./movetonextnamespace/)() | Moves the [XPathNavigator](./) to the next namespace node. |
| virtual [MoveToParent](./movetoparent/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the parent node of the current node. |
| virtual [MoveToPrevious](./movetoprevious/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the previous sibling node of the current node. |
| virtual [MoveToRoot](./movetoroot/)() | Moves the [XPathNavigator](./) to the root node that the current node belongs to. |
| virtual [PrependChild](./prependchild/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create a new child node at the beginning of the list of child nodes of the current node. |
| virtual [PrependChild](./prependchild/)(String) | Creates a new child node at the beginning of the list of child nodes of the current node using the XML string specified. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlReader\>) | Creates a new child node at the beginning of the list of child nodes of the current node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XPathNavigator\>) | Creates a new child node at the beginning of the list of child nodes of the current node using the nodes in the [XPathNavigator](./) object specified. |
| virtual [PrependChildElement](./prependchildelement/)(String, String, String, String) | Creates a new child element at the beginning of the list of child nodes of the current node using the namespace prefix, local name, and namespace URI specified with the value specified. |
| virtual [ReadSubtree](./readsubtree/)() | Returns an [XmlReader](../../system.xml/xmlreader/) object that contains the current node and its child nodes. |
| virtual [ReplaceRange](./replacerange/)(SharedPtr\<XPathNavigator\>) | Replaces a range of sibling nodes from the current node to the node specified. |
| virtual [ReplaceSelf](./replaceself/)(String) | Replaces the current node with the content of the string specified. |
| virtual [ReplaceSelf](./replaceself/)(SharedPtr\<XmlReader\>) | Replaces the current node with the contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual [ReplaceSelf](./replaceself/)(SharedPtr\<XPathNavigator\>) | Replaces the current node with the contents of the [XPathNavigator](./) object specified. |
| virtual [Select](./select/)(String) | Selects a node set, using the specified [XPath](../) expression. |
| virtual [Select](./select/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Selects a node set using the specified [XPath](../) expression with the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
| virtual [Select](./select/)(SharedPtr\<XPathExpression\>) | Selects a node set using the specified [XPathExpression](../xpathexpression/). |
| virtual [SelectAncestors](./selectancestors/)(XPathNodeType, bool) | Selects all the ancestor nodes of the current node that have a matching [XPathNodeType](../xpathnodetype/). |
| virtual [SelectAncestors](./selectancestors/)(String, String, bool) | Selects all the ancestor nodes of the current node that have the specified local name and namespace URI. |
| virtual [SelectChildren](./selectchildren/)(XPathNodeType) | Selects all the child nodes of the current node that have the matching [XPathNodeType](../xpathnodetype/). |
| virtual [SelectChildren](./selectchildren/)(String, String) | Selects all the child nodes of the current node that have the local name and namespace URI specified. |
| virtual [SelectDescendants](./selectdescendants/)(XPathNodeType, bool) | Selects all the descendant nodes of the current node that have a matching [XPathNodeType](../xpathnodetype/). |
| virtual [SelectDescendants](./selectdescendants/)(String, String, bool) | Selects all the descendant nodes of the current node with the local name and namespace URI specified. |
| virtual [SelectSingleNode](./selectsinglenode/)(String) | Selects a single node in the [XPathNavigator](./) using the specified [XPath](../) query. |
| virtual [SelectSingleNode](./selectsinglenode/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Selects a single node in the [XPathNavigator](./) object using the specified [XPath](../) query with the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
| virtual [SelectSingleNode](./selectsinglenode/)(SharedPtr\<XPathExpression\>) | Selects a single node in the [XPathNavigator](./) using the specified [XPathExpression](../xpathexpression/) object. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Sets the markup representing the child nodes of the current node. |
| virtual [set_OuterXml](./set_outerxml/)(String) | Sets the markup representing the opening and closing tags of the current node and its child nodes. |
| virtual [SetTypedValue](./settypedvalue/)(SharedPtr\<Object\>) | Sets the typed value of the current node. |
| virtual [SetValue](./setvalue/)(String) | Sets the value of the current node. |
| [ToString](./tostring/)() const override | Returns the text value of the current node. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Returns the current node's value as the Type specified, using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
| virtual [WriteSubtree](./writesubtree/)(SharedPtr\<XmlWriter\>) | Streams the current node and its child nodes to the [XmlWriter](../../system.xml/xmlwriter/) object specified. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [XPathItem](../xpathitem/)
* Class [IXPathNavigable](../ixpathnavigable/)
* Class [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
