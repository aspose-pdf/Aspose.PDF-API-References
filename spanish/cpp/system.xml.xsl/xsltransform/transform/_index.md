---
title: "Método Transform de System::Xml::Xsl::XslTransform"
linktitle: "Transform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XslTransform::Transform method. Transforma los datos XML en el IXPathNavigable usando los args especificados y envía el resultado a un XmlReader en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |

### ReturnValue

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que el método [XslTransform::Transform](./) se complete. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

### ReturnValue

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |

### ReturnValue

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

### ReturnValue

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Transforma los datos XML en el XPathNavigator usando los args especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el XPathNavigator usando los args especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const SharedPtr\<XsltArgumentList\>\& | Una [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se complete. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const String\&, const String\&) method


Transforma los datos XML en el archivo de entrada y devuelve el resultado a un archivo de salida.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivoEntrada | const String\& | La URL del documento fuente que se va a transformar. |
| archivoSalida | const String\& | La URL del archivo de salida. |

## Ver también

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Transforma los datos XML en el archivo de entrada y devuelve el resultado a un archivo de salida.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivoEntrada | const String\& | La URL del documento fuente que se va a transformar. |
| archivoSalida | const String\& | La URL del archivo de salida. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que el método [XslTransform::Transform](./) se complete. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
