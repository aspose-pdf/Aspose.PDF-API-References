---
title: "System::Xml::Xsl::XslTransform::Load method"
linktitle: "Load"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XslTransform::Load method. Carga la hoja de estilo XSLT contenida en el IXPathNavigable en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Carga la hoja de estilo XSLT contenida en el IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene la hoja de estilo XSLT. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Carga la hoja de estilo XSLT contenida en el IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene la hoja de estilo XSLT. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para cargar cualquier hoja de estilo referenciada en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, los recursos externos no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


Carga la hoja de estilo XSLT contenida en el XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hoja de estilo | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un objeto XPathNavigator que contiene la hoja de estilo XSLT. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Carga la hoja de estilo XSLT contenida en el XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hoja de estilo | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Un objeto XPathNavigator que contiene la hoja de estilo XSLT. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para cargar cualquier hoja de estilo referenciada en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, los recursos externos no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


Carga la hoja de estilo XSLT contenida en el [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo XSLT. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Carga la hoja de estilo XSLT contenida en el [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo XSLT. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para cargar cualquier hoja de estilo referenciada en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, los recursos externos no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const String\&) method


Carga la hoja de estilo XSLT especificada por una URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL que especifica la hoja de estilo XSLT a cargar. |

## Ver también

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Carga la hoja de estilo XSLT especificada por una URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL que especifica la hoja de estilo XSLT a cargar. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) a usar para cargar la hoja de estilo y cualquier(s) hoja(s) de estilo referenciada(s) en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, se utiliza un [XmlUrlResolver](../../../system.xml/xmlurlresolver/) predeterminado sin credenciales de usuario para abrir la hoja de estilo. El [XmlUrlResolver](../../../system.xml/xmlurlresolver/) predeterminado no se usa para resolver recursos externos en la hoja de estilo, por lo que los elementos **xsl:import** y **xsl:include** no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
