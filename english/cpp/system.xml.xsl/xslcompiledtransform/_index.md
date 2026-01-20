---
title: System::Xml::Xsl::XslCompiledTransform class
linktitle: XslCompiledTransform
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XslCompiledTransform class. Transforms XML data using an XSLT style sheet in C++.'
type: docs
weight: 300
url: /cpp/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform class


Transforms XML data using an XSLT style sheet.

```cpp
class XslCompiledTransform : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_OutputSettings](./get_outputsettings/)() | Returns an [XmlWriterSettings](../../system.xml/xmlwritersettings/) object that contains the output information derived from the **xsl:output** element of the style sheet. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Compiles the style sheet contained in the [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Compiles the XSLT style sheet contained in the [XmlReader](../../system.xml/xmlreader/). The [XmlResolver](../../system.xml/xmlresolver/) resolves any XSLT **import** or **include** elements and the XSLT settings determine the permissions for the style sheet. |
| [Load](./load/)(const String\&) | Loads and compiles the style sheet located at the specified URI. |
| [Load](./load/)(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Loads and compiles the XSLT style sheet specified by the URI. The [XmlResolver](../../system.xml/xmlresolver/) resolves any XSLT **import** or **include** elements and the XSLT settings determine the permissions for the style sheet. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Compiles the style sheet contained in the IXPathNavigable object. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) | Compiles the XSLT style sheet contained in the IXPathNavigable. The [XmlResolver](../../system.xml/xmlresolver/) resolves any XSLT **import** or **include** elements and the XSLT settings determine the permissions for the style sheet. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) | Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an TextWriter. The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to a stream. The [XsltArgumentList](../xsltargumentlist/) provides additional runtime arguments. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) | Executes the transform using the input document specified by the [XmlReader](../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Executes the transform using the input document specified by the [XmlReader](../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Executes the transform using the input document specified by the [XmlReader](../../system.xml/xmlreader/) object and outputs the results to a TextWriter. The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Executes the transform using the input document specified by the [XmlReader](../../system.xml/xmlreader/) object and outputs the results to a stream. The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XmlWriter\>\&) | Executes the transform using the input document specified by the URI and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Executes the transform using the input document specified by the URI and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Executes the transform using the input document specified by the URI and outputs the results to a TextWriter. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Executes the transform using the input document specified by the URI and outputs the results to stream. The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments. |
| [Transform](./transform/)(const String\&, const String\&) | Executes the transform using the input document specified by the URI and outputs the results to a file. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Executes the transform using the input document specified by the [XmlReader](../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments and the [XmlResolver](../../system.xml/xmlresolver/) resolves the XSLT **document()** function. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Executes the transform by using the input document that is specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../system.xml/xmlwriter/). The [XsltArgumentList](../xsltargumentlist/) provides additional run-time arguments and the [XmlResolver](../../system.xml/xmlresolver/) resolves the XSLT **document()** function. |
| [XslCompiledTransform](./xslcompiledtransform/)() | Initializes a new instance of the [XslCompiledTransform](./) class. |
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
