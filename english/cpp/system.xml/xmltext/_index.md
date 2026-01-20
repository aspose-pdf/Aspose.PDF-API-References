---
title: System::Xml::XmlText class
linktitle: XmlText
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlText class. Represents the text content of an element or attribute in C++.'
type: docs
weight: 3800
url: /cpp/system.xml/xmltext/
---
## XmlText class


Represents the text content of an element or attribute.

```cpp
class XmlText : public System::Xml::XmlCharacterData
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_PreviousText](./get_previoustext/)() override | Returns the text node that immediately precedes this node. |
| [get_Value](./get_value/)() override | Returns the value of the node. |
| [set_Value](./set_value/)(String) override | Sets the value of the node. |
| virtual [SplitText](./splittext/)(int32_t) | Splits the node into two nodes at the specified offset, keeping both in the tree as siblings. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). [XmlText](./) nodes do not have children, so this method has no effect. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the node to the specified [XmlWriter](../xmlwriter/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlCharacterData](../xmlcharacterdata/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
