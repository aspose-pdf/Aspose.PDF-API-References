---
title: System::Xml::Xsl::XslTransform::Transform method
linktitle: Transform
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XslTransform::Transform method. Transforms the XML data in the IXPathNavigable using the specified args and outputs the result to an XmlReader in C++.'
type: docs
weight: 400
url: /cpp/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |

### ReturnValue

An [XmlReader](../../../system.xml/xmlreader/) containing the results of the transformation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the [XslTransform::Transform](./) method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

### ReturnValue

An [XmlReader](../../../system.xml/xmlreader/) containing the results of the transformation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to an [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |

### ReturnValue

An [XmlReader](../../../system.xml/xmlreader/) containing the results of the transformation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::Stream\>\& | The stream to which you want to output. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<IO::TextWriter\>\& | The TextWriter to which you want to output. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to an [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

### ReturnValue

An [XmlReader](../../../system.xml/xmlreader/) containing the results of the transformation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Transforms the XML data in the XPathNavigator using the specified args and outputs the result to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the XPathNavigator using the specified args and outputs the result to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | An XPathNavigator containing the data to be transformed. |
| args | const SharedPtr\<XsltArgumentList\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const SharedPtr\<XmlWriter\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const String\&, const String\&) method


Transforms the XML data in the input file and outputs the result to an output file.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const String\& | The URL of the source document to be transformed. |
| outputfile | const String\& | The URL of the output file. |

## See Also

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforms the XML data in the input file and outputs the result to an output file.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const String\& | The URL of the source document to be transformed. |
| outputfile | const String\& | The URL of the output file. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the [XslTransform::Transform](./) method completes. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
