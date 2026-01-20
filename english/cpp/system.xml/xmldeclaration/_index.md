---
title: System::Xml::XmlDeclaration class
linktitle: XmlDeclaration
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDeclaration class. Represents the XML declaration node <?xml version=''1.0''...?> in C++.'
type: docs
weight: 1300
url: /cpp/system.xml/xmldeclaration/
---
## XmlDeclaration class


Represents the XML declaration node **<?xml version='1.0'...?>**.

```cpp
class XmlDeclaration : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_Encoding](./get_encoding/)() | Returns the encoding level of the XML document. |
| [get_InnerText](./get_innertext/)() override | Returns the concatenated values of the [XmlDeclaration](./). |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_Standalone](./get_standalone/)() | Returns the value of the standalone attribute. |
| [get_Value](./get_value/)() override | Returns the value of the [XmlDeclaration](./). |
| [get_Version](./get_version/)() | Returns the XML version of the document. |
| [set_Encoding](./set_encoding/)(const String\&) | Sets the encoding level of the XML document. |
| [set_InnerText](./set_innertext/)(String) override | Sets the concatenated values of the [XmlDeclaration](./). |
| [set_Standalone](./set_standalone/)(const String\&) | Sets the value of the standalone attribute. |
| [set_Value](./set_value/)(String) override | Sets the value of the [XmlDeclaration](./). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the children of the node to the specified [XmlWriter](../xmlwriter/). Because [XmlDeclaration](./) nodes do not have children, this method has no effect. |
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
