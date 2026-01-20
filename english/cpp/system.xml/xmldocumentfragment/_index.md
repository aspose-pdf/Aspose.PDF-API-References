---
title: System::Xml::XmlDocumentFragment class
linktitle: XmlDocumentFragment
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocumentFragment class. Represents a lightweight object that is useful for tree insert operations in C++.'
type: docs
weight: 1500
url: /cpp/system.xml/xmldocumentfragment/
---
## XmlDocumentFragment class


Represents a lightweight object that is useful for tree insert operations.

```cpp
class XmlDocumentFragment : public System::Xml::XmlNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_InnerXml](./get_innerxml/)() override | Returns the markup representing the children of this node. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returns the [XmlDocument](../xmldocument/) to which this node belongs. |
| [set_InnerXml](./set_innerxml/)(String) override | Sets the markup representing the children of this node. |
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
