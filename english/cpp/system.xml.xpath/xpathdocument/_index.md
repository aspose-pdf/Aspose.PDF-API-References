---
title: System::Xml::XPath::XPathDocument class
linktitle: XPathDocument
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathDocument class. Provides a fast, read-only, in-memory representation of an XML document by using the XPath data model in C++.'
type: docs
weight: 200
url: /cpp/system.xml.xpath/xpathdocument/
---
## XPathDocument class


Provides a fast, read-only, in-memory representation of an XML document by using the [XPath](../) data model.

```cpp
class XPathDocument : public System::Xml::XPath::IXPathNavigable
```

## Methods

| Method | Description |
| --- | --- |
| [CreateNavigator](./createnavigator/)() override | Initializes a read-only [XPathNavigator](../xpathnavigator/) object for navigating through nodes in this [XPathDocument](./). |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&) | Initializes a new instance of the [XPathDocument](./) class from the XML data that is contained in the specified [XmlReader](../../system.xml/xmlreader/) object. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&, XmlSpace) | Initializes a new instance of the [XPathDocument](./) class from the XML data that is contained in the specified [XmlReader](../../system.xml/xmlreader/) object with the specified white space handling. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::TextReader\>\&) | Initializes a new instance of the [XPathDocument](./) class from the XML data that is contained in the specified TextReader object. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::Stream\>\&) | Initializes a new instance of the [XPathDocument](./) class from the XML data in the specified Stream object. |
| [XPathDocument](./xpathdocument/)(const String\&) | Initializes a new instance of the [XPathDocument](./) class from the XML data in the specified file. |
| [XPathDocument](./xpathdocument/)(const String\&, XmlSpace) | Initializes a new instance of the [XPathDocument](./) class from the XML data in the file specified with the white space handling specified. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IXPathNavigable](../ixpathnavigable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
