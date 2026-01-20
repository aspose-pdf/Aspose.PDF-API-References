---
title: System::Xml::XmlNotation class
linktitle: XmlNotation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNotation class. Represents a notation declaration, such as <!NOTATION... > in C++.'
type: docs
weight: 2900
url: /cpp/system.xml/xmlnotation/
---
## XmlNotation class


Represents a notation declaration, such as **<!NOTATION... >**.

```cpp
class XmlNotation : public System::Xml::XmlNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an [XmlNotation](./) object throws an exception. |
| [get_InnerXml](./get_innerxml/)() override | Returns the markup representing the children of this node. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returns a value indicating whether the node is read-only. |
| [get_LocalName](./get_localname/)() override | Returns the name of the current node without the namespace prefix. |
| [get_Name](./get_name/)() override | Returns the name of the current node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_OuterXml](./get_outerxml/)() override | Returns the markup representing this node and all its children. |
| [get_PublicId](./get_publicid/)() | Returns the value of the public identifier on the notation declaration. |
| [get_SystemId](./get_systemid/)() | Returns the value of the system identifier on the notation declaration. |
| [set_InnerXml](./set_innerxml/)(String) override | Sets the markup representing the children of this node. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the children of the node to the specified [XmlWriter](../xmlwriter/). This method has no effect on [XmlNotation](./) nodes. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the node to the specified [XmlWriter](../xmlwriter/). This method has no effect on [XmlNotation](./) nodes. |
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
