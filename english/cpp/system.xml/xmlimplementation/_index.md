---
title: System::Xml::XmlImplementation class
linktitle: XmlImplementation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlImplementation class. Defines the context for a set of XmlDocument objects in C++.'
type: docs
weight: 2000
url: /cpp/system.xml/xmlimplementation/
---
## XmlImplementation class


Defines the context for a set of [XmlDocument](../xmldocument/) objects.

```cpp
class XmlImplementation : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CreateDocument](./createdocument/)() | Creates a new [XmlDocument](../xmldocument/). |
| [HasFeature](./hasfeature/)(const String\&, const String\&) | Tests if the Document [Object](../../system/object/) Model (DOM) implementation implements a specific feature. |
| [XmlImplementation](./xmlimplementation/)() | Initializes a new instance of the [XmlImplementation](./) class. |
| [XmlImplementation](./xmlimplementation/)(const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlImplementation](./) class with the [XmlNameTable](../xmlnametable/) specified. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
