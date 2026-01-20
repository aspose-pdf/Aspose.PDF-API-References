---
title: System::Xml::XmlElement class
linktitle: XmlElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement class. Represents an element in C++.'
type: docs
weight: 1700
url: /cpp/system.xml/xmlelement/
---
## XmlElement class


Represents an element.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Returns a **bool** value indicating whether the current node has any attributes. |
| [get_InnerText](./get_innertext/)() override | Returns the concatenated values of the node and all its children. |
| [get_InnerXml](./get_innerxml/)() override | Returns the markup representing just the children of this node. |
| [get_IsEmpty](./get_isempty/)() | Returns the tag format of the element. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the current node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returns the namespace URI of this node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returns the [XmlDocument](../xmldocument/) to which this node belongs. |
| [get_Prefix](./get_prefix/)() override | Returns the namespace prefix of this node. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returns the post schema validation infoset that has been assigned to this node as a result of schema validation. |
| virtual [GetAttribute](./getattribute/)(String) | Returns the value for the attribute with the specified name. |
| virtual [GetAttribute](./getattribute/)(String, String) | Returns the value for the attribute with the specified local name and namespace URI. |
| virtual [GetAttributeNode](./getattributenode/)(String) | Returns the [XmlAttribute](../xmlattribute/) with the specified name. |
| virtual [GetAttributeNode](./getattributenode/)(String, String) | Returns the [XmlAttribute](../xmlattribute/) with the specified local name and namespace URI. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Returns an [XmlNodeList](../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_Name](./get_name/). |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Returns an [XmlNodeList](../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_LocalName](./get_localname/) and [XmlElement::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual [HasAttribute](./hasattribute/)(String) | Determines whether the current node has an attribute with the specified name. |
| virtual [HasAttribute](./hasattribute/)(String, String) | Determines whether the current node has an attribute with the specified local name and namespace URI. |
| [RemoveAll](./removeall/)() override | Removes all specified attributes and children of the current node. Default attributes are not removed. |
| virtual [RemoveAllAttributes](./removeallattributes/)() | Removes all specified attributes from the element. Default attributes are not removed. |
| virtual [RemoveAttribute](./removeattribute/)(String) | Removes an attribute by name. |
| virtual [RemoveAttribute](./removeattribute/)(String, String) | Removes an attribute with the specified local name and namespace URI. (If the removed attribute has a default value, it is immediately replaced). |
| virtual [RemoveAttributeAt](./removeattributeat/)(int32_t) | Removes the attribute node with the specified index from the element. (If the removed attribute has a default value, it is immediately replaced). |
| virtual [RemoveAttributeNode](./removeattributenode/)(SharedPtr\<XmlAttribute\>) | Removes the specified [XmlAttribute](../xmlattribute/). |
| virtual [RemoveAttributeNode](./removeattributenode/)(String, String) | Removes the [XmlAttribute](../xmlattribute/) specified by the local name and namespace URI. (If the removed attribute has a default value, it is immediately replaced). |
| [set_InnerText](./set_innertext/)(String) override | Sets the concatenated values of the node and all its children. |
| [set_InnerXml](./set_innerxml/)(String) override | Sets the markup representing just the children of this node. |
| [set_IsEmpty](./set_isempty/)(bool) | Sets the tag format of the element. |
| [set_Prefix](./set_prefix/)(String) override | Sets the namespace prefix of this node. |
| virtual [SetAttribute](./setattribute/)(String, String) | Sets the value of the attribute with the specified name. |
| virtual [SetAttribute](./setattribute/)(String, String, String) | Sets the value of the attribute with the specified local name and namespace URI. |
| virtual [SetAttributeNode](./setattributenode/)(SharedPtr\<XmlAttribute\>) | Adds the specified [XmlAttribute](../xmlattribute/). |
| virtual [SetAttributeNode](./setattributenode/)(String, String) | Adds the specified [XmlAttribute](../xmlattribute/). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the current node to the specified [XmlWriter](../xmlwriter/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
