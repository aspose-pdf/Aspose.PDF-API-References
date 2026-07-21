---
title: "System::Xml::Xsl::XslCompiledTransform class"
linktitle: "XslCompiledTransform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XslCompiledTransform class. Transforma datos XML usando una hoja de estilo XSLT en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform class


Transforma datos XML usando una hoja de estilo XSLT.

```cpp
class XslCompiledTransform : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_OutputSettings](./get_outputsettings/)() | Devuelve un objeto [XmlWriterSettings](../../system.xml/xmlwritersettings/) que contiene la información de salida derivada del elemento **xsl:output** de la hoja de estilo. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Compila la hoja de estilo contenida en el [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Compila la hoja de estilo XSLT contenida en el [XmlReader](../../system.xml/xmlreader/). El [XmlResolver](../../system.xml/xmlresolver/) resuelve cualquier elemento XSLT **import** o **include** y la configuración de XSLT determina los permisos para la hoja de estilo. |
| [Load](./load/)(const String\&) | Carga y compila la hoja de estilo ubicada en la URI especificada. |
| [Load](./load/)(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Carga y compila la hoja de estilo XSLT especificada por la URI. El [XmlResolver](../../system.xml/xmlresolver/) resuelve cualquier elemento XSLT **import** o **include** y la configuración de XSLT determina los permisos para la hoja de estilo. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Compila la hoja de estilo contenida en el objeto IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) | Compila la hoja de estilo XSLT contenida en el IXPathNavigable. El [XmlResolver](../../system.xml/xmlresolver/) resuelve cualquier elemento XSLT **import** o **include** y la configuración de XSLT determina los permisos para la hoja de estilo. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un TextWriter. El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un flujo. El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../system.xml/xmlreader/) y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../system.xml/xmlreader/) y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../system.xml/xmlreader/) y envía los resultados a un TextWriter. El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../system.xml/xmlreader/) y envía los resultados a un flujo. El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XmlWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un TextWriter. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un flujo. El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales. |
| [Transform](./transform/)(const String\&, const String\&) | Ejecuta la transformación usando el documento de entrada especificado por la URI y envía los resultados a un archivo. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../system.xml/xmlreader/) y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales y el [XmlResolver](../../system.xml/xmlresolver/) resuelve la función XSLT **document()**. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y envía los resultados a un [XmlWriter](../../system.xml/xmlwriter/). El [XsltArgumentList](../xsltargumentlist/) proporciona argumentos de tiempo de ejecución adicionales y el [XmlResolver](../../system.xml/xmlresolver/) resuelve la función XSLT **document()**. |
| [XslCompiledTransform](./xslcompiledtransform/)() | Inicializa una nueva instancia de la clase [XslCompiledTransform](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
