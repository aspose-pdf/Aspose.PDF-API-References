---
title: System::Xml::XmlAttribute class
linktitle: XmlAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttribute class. Represents an attribute. Valid and default values for the attribute are defined in a document type definition (DTD) or schema in C++.'
type: docs
weight: 600
url: /cpp/system.xml/xmlattribute/
---
## XmlAttribute class


Represents an attribute. Valid and default values for the attribute are defined in a document type definition (DTD) or schema.

```cpp
class XmlAttribute : public System::Xml::XmlNode
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) override | Adds the specified node to the end of the list of child nodes, of this node. |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base Uniform Resource Identifier (URI) of the node. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returns the namespace URI of this node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returns the [XmlDocument](../xmldocument/) to which this node belongs. |
| virtual [get_OwnerElement](./get_ownerelement/)() | Returns the [XmlElement](../xmlelement/) to which the attribute belongs. |
| [get_Prefix](./get_prefix/)() override | Returns the namespace prefix of this node. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returns the post-schema-validation-infoset that has been assigned to this node as a result of schema validation. |
| virtual [get_Specified](./get_specified/)() | Returns a value indicating whether the attribute value was explicitly set. |
| [get_Value](./get_value/)() override | Returns the value of the node. |
| [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Inserts the specified node immediately after the specified reference node. |
| [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Inserts the specified node immediately before the specified reference node. |
| [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) override | Adds the specified node to the beginning of the list of child nodes for this node. |
| [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) override | Removes the specified child node. |
| [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Replaces the child node specified with the new child node specified. |
| [set_InnerText](./set_innertext/)(String) override | Sets the concatenated values of the node and all its children. |
| [set_InnerXml](./set_innerxml/)(String) override | Sets the value of the attribute. |
| [set_Prefix](./set_prefix/)(String) override | Sets the namespace prefix of this node. |
| [set_Value](./set_value/)(String) override | Sets the value of the node. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the node to the specified [XmlWriter](../xmlwriter/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
