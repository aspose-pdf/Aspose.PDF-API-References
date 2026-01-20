---
title: System::Xml::XmlEntityReference class
linktitle: XmlEntityReference
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlEntityReference class. Represents an entity reference node in C++.'
type: docs
weight: 1900
url: /cpp/system.xml/xmlentityreference/
---
## XmlEntityReference class


Represents an entity reference node.

```cpp
class XmlEntityReference : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_BaseURI](./get_baseuri/)() override | Returns the base Uniform Resource Identifier (URI) of the current node. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returns a value indicating whether the node is read-only. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the node. |
| [get_Value](./get_value/)() override | Returns the value of the node. |
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

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
