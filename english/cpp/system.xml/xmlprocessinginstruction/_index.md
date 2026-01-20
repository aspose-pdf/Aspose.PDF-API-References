---
title: System::Xml::XmlProcessingInstruction class
linktitle: XmlProcessingInstruction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlProcessingInstruction class. Represents a processing instruction, which XML defines to keep processor-specific information in the text of the document in C++.'
type: docs
weight: 3100
url: /cpp/system.xml/xmlprocessinginstruction/
---
## XmlProcessingInstruction class


Represents a processing instruction, which XML defines to keep processor-specific information in the text of the document.

```cpp
class XmlProcessingInstruction : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_Data](./get_data/)() | Returns the content of the processing instruction, excluding the target. |
| [get_InnerText](./get_innertext/)() override | Returns the concatenated values of the node and all its children. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_Target](./get_target/)() | Returns the target of the processing instruction. |
| [get_Value](./get_value/)() override | Returns the value of the node. |
| [set_Data](./set_data/)(const String\&) | Sets the content of the processing instruction, excluding the target. |
| [set_InnerText](./set_innertext/)(String) override | Sets the concatenated values of the node and all its children. |
| [set_Value](./set_value/)(String) override | Sets the value of the node. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). Because ProcessingInstruction nodes do not have children, this method has no effect. |
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
