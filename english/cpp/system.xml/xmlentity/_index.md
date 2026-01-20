---
title: System::Xml::XmlEntity class
linktitle: XmlEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlEntity class. Represents an entity declaration, such as <!ENTITY... > in C++.'
type: docs
weight: 1800
url: /cpp/system.xml/xmlentity/
---
## XmlEntity class


Represents an entity declaration, such as **<!ENTITY... >**.

```cpp
class XmlEntity : public System::Xml::XmlNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. Entity nodes cannot be cloned. Calling this method on an [XmlEntity](./) object throws an exception. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base Uniform Resource Identifier (URI) of the current node. |
| [get_InnerText](./get_innertext/)() override | Returns the concatenated values of the entity node and all its children. |
| [get_InnerXml](./get_innerxml/)() override | Returns the markup representing the children of this node. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returns a value indicating whether the node is read-only. |
| [get_LocalName](./get_localname/)() override | Returns the name of the node without the namespace prefix. |
| [get_Name](./get_name/)() override | Returns the name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the node. |
| [get_NotationName](./get_notationname/)() | Returns the name of the optional NDATA attribute on the entity declaration. |
| [get_OuterXml](./get_outerxml/)() override | Returns the markup representing this node and all its children. |
| [get_PublicId](./get_publicid/)() | Returns the value of the public identifier on the entity declaration. |
| [get_SystemId](./get_systemid/)() | Returns the value of the system identifier on the entity declaration. |
| [set_InnerText](./set_innertext/)(String) override | Sets the concatenated values of the entity node and all its children. |
| [set_InnerXml](./set_innerxml/)(String) override | Sets the markup representing the children of this node. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). For [XmlEntity](./) nodes, this method has no effect. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the node to the specified [XmlWriter](../xmlwriter/). For [XmlEntity](./) nodes, this method has no effect. |
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
