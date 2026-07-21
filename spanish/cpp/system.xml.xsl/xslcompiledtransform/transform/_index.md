---
title: "Método System::Xml::Xsl::XslCompiledTransform::Transform"
linktitle: "Transform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Xsl::XslCompiledTransform::Transform. Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un XmlWriter en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un flujo. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| resultados | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un TextWriter. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| resultados | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Ejecuta la transformación usando el documento de entrada que se especifica mediante el objeto IXPathNavigable y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución y el [XmlResolver](../../../system.xml/xmlresolver/) resuelve la función XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | El documento a transformar que se especifica mediante el objeto IXPathNavigable. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Lista de argumentos como [XsltArgumentList](../../xsltargumentlist/). |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que deseas enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, deberías crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) que se devuelve del valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |
| documentResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si es **nullptr**, la función **document()** no se resuelve. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | El [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y envía los resultados a un flujo. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| resultados | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y envía los resultados a un TextWriter. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| resultados | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución y el [XmlResolver](../../../system.xml/xmlresolver/) resuelve la función XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<XmlReader\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |
| documentResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si es **nullptr**, la función **document()** no se resuelve. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | La URI del documento de entrada. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un flujo. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | La URI del documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| resultados | const SharedPtr\<IO::Stream\>\& | El flujo al que desea enviar la salida. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [Stream](../../../system.io/stream/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | La URI del documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| resultados | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea enviar la salida. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | La URI del documento de entrada. |
| arguments | const SharedPtr\<XsltArgumentList\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const SharedPtr\<XmlWriter\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Transform(const String\&, const String\&) method


Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un archivo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | La URI del documento de entrada. |
| resultsFile | const String\& | La URI del archivo de salida. |

## Ver también

* Class [String](../../../system/string/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
