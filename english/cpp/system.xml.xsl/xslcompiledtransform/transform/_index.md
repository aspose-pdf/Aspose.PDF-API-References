---
title: System::Xml::Xsl::XslCompiledTransform::Transform method
linktitle: Transform
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XslCompiledTransform::Transform method. Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an XmlWriter in C++.'
type: docs
weight: 400
url: /cpp/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to a stream. The [XsltArgumentList](../../xsltargumentlist/) provides additional runtime arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an TextWriter. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Executes the transform by using the input document that is specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments and the [XmlResolver](../../../system.xml/xmlresolver/) resolves the XSLT **document()** function.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | The document to transform that is specified by the IXPathNavigable object. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Argument list as [XsltArgumentList](../../xsltargumentlist/). |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) by using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object that is returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |
| documentResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | The [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to a stream. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to a TextWriter. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments and the [XmlResolver](../../../system.xml/xmlresolver/) resolves the XSLT **document()** function.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |
| documentResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI of the input document. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to stream. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI of the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to a TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI of the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI of the input document. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const String\&) method


Executes the transform using the input document specified by the URI and outputs the results to a file.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const String\& | The URI of the input document. |
| resultsFile | const String\& | The URI of the output file. |

## See Also

* Class [String](../../../system/string/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
