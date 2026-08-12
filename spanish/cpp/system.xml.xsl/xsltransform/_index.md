---
title: "Clase System::Xml::Xsl::XslTransform"
linktitle: "XslTransform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Xsl::XslTransform. Transforma datos XML usando una hoja de estilo Extensible Stylesheet Language for Transformations (XSLT) en C++."
type: docs
weight: 700
url: /es/cpp/system.xml.xsl/xsltransform/
---
## XslTransform class


Transforma datos XML usando una hoja de estilo Extensible Stylesheet Language for Transformations (XSLT).

```cpp
class XslTransform : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Carga la hoja de estilo XSLT contenida en el [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Carga la hoja de estilo XSLT contenida en el [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Carga la hoja de estilo XSLT contenida en el IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Carga la hoja de estilo XSLT contenida en el IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) | Carga la hoja de estilo XSLT contenida en el XPathNavigator. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Carga la hoja de estilo XSLT contenida en el XPathNavigator. |
| [Load](./load/)(const String\&) | Carga la hoja de estilo XSLT especificada por una URL. |
| [Load](./load/)(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Carga la hoja de estilo XSLT especificada por una URL. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Establece el [XmlResolver](../../system.xml/xmlresolver/) utilizado para resolver recursos externos cuando se llama al método [XslTransform::Transform](./transform/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) | Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el XPathNavigator usando los argumentos especificados y devuelve el resultado a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Transforma los datos XML en el XPathNavigator usando los argumentos especificados y devuelve el resultado a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Transforma los datos XML en el XPathNavigator usando los **args** especificados y devuelve el resultado a un TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Transforma los datos XML en el IXPathNavigable usando los **args** especificados y devuelve el resultado a un [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transforma los datos XML en el archivo de entrada y devuelve el resultado a un archivo de salida. |
| [Transform](./transform/)(const String\&, const String\&) | Transforma los datos XML en el archivo de entrada y devuelve el resultado a un archivo de salida. |
| [XslTransform](./xsltransform/)() | Inicializa una nueva instancia de la clase [XslTransform](./). |
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
