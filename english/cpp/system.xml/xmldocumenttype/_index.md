---
title: System::Xml::XmlDocumentType class
linktitle: XmlDocumentType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocumentType class. Represents the document type declaration in C++.'
type: docs
weight: 1600
url: /cpp/system.xml/xmldocumenttype/
---
## XmlDocumentType class


Represents the document type declaration.

```cpp
class XmlDocumentType : public System::Xml::XmlLinkedNode
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_Entities](./get_entities/)() | Returns the collection of [XmlEntity](../xmlentity/) nodes declared in the document type declaration. |
| [get_InternalSubset](./get_internalsubset/)() | Returns the value of the document type definition (DTD) internal subset on the DOCTYPE declaration. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returns a value indicating whether the node is read-only. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [get_Notations](./get_notations/)() | Returns the collection of [XmlNotation](../xmlnotation/) nodes present in the document type declaration. |
| [get_PublicId](./get_publicid/)() | Returns the value of the public identifier on the DOCTYPE declaration. |
| [get_SystemId](./get_systemid/)() | Returns the value of the system identifier on the DOCTYPE declaration. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). For [XmlDocumentType](./) nodes, this method has no effect. |
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
