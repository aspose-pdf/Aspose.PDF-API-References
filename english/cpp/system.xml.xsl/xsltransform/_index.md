---
title: System::Xml::Xsl::XslTransform class
linktitle: XslTransform
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XslTransform class. Transforms XML data using an Extensible Stylesheet Language for Transformations (XSLT) style sheet in C++.'
type: docs
weight: 700
url: /cpp/system.xml.xsl/xsltransform/
---
## XslTransform class


Transforms XML data using an Extensible Stylesheet Language for Transformations (XSLT) style sheet.

```cpp
class XslTransform : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Loads the XSLT style sheet contained in the [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Loads the XSLT style sheet contained in the [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Loads the XSLT style sheet contained in the IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Loads the XSLT style sheet contained in the IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) | Loads the XSLT style sheet contained in the XPathNavigator. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Loads the XSLT style sheet contained in the XPathNavigator. |
| [Load](./load/)(const String\&) | Loads the XSLT style sheet specified by a URL. |
| [Load](./load/)(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Loads the XSLT style sheet specified by a URL. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Sets the [XmlResolver](../../system.xml/xmlresolver/) used to resolve external resources when the [XslTransform::Transform](./transform/) method is called. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the XPathNavigator using the specified args and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Transforms the XML data in the XPathNavigator using the specified args and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforms the XML data in the input file and outputs the result to an output file. |
| [Transform](./transform/)(const String\&, const String\&) | Transforms the XML data in the input file and outputs the result to an output file. |
| [XslTransform](./xsltransform/)() | Initializes a new instance of the [XslTransform](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
