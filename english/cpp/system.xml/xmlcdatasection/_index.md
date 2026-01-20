---
title: System::Xml::XmlCDataSection class
linktitle: XmlCDataSection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlCDataSection class. Represents a CDATA section in C++.'
type: docs
weight: 800
url: /cpp/system.xml/xmlcdatasection/
---
## XmlCDataSection class


Represents a CDATA section.

```cpp
class XmlCDataSection : public System::Xml::XmlCharacterData
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_PreviousText](./get_previoustext/)() override | Returns the text node that immediately precedes this node. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the children of the node to the specified [XmlWriter](../xmlwriter/). |
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
