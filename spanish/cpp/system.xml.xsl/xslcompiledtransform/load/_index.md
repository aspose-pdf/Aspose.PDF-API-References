---
title: "System::Xml::Xsl::XslCompiledTransform::Load método"
linktitle: "Load"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XslCompiledTransform::Load método. Compila la hoja de estilo contenida en el objeto IXPathNavigable en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Compila la hoja de estilo contenida en el objeto IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene la hoja de estilo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) method


Compila la hoja de estilo XSLT contenida en el IXPathNavigable. El [XmlResolver](../../../system.xml/xmlresolver/) resuelve cualquier elemento XSLT **import** o **include** y la configuración XSLT determina los permisos para la hoja de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene la hoja de estilo. |
| settings | SharedPtr\<XsltSettings\> | Los [XsltSettings](../../xsltsettings/) a aplicar a la hoja de estilo. Si esto es **nullptr**, se aplica la configuración [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | SharedPtr\<XmlResolver\> | El [XmlResolver](../../../system.xml/xmlresolver/) se utiliza para resolver cualquier hoja de estilo referenciada en los elementos **import** y **include** de XSLT. Si esto es **nullptr**, los recursos externos no se resuelven. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) method


Compila la hoja de estilo contenida en el [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


Compila la hoja de estilo XSLT contenida en el [XmlReader](../../../system.xml/xmlreader/). El [XmlResolver](../../../system.xml/xmlresolver/) resuelve cualquier elemento **import** o **include** de XSLT y la configuración de XSLT determina los permisos para la hoja de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | El [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo. |
| settings | const SharedPtr\<XsltSettings\>\& | Los [XsltSettings](../../xsltsettings/) a aplicar a la hoja de estilo. Si esto es **nullptr**, se aplica la configuración [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) se utiliza para resolver cualquier hoja de estilo referenciada en los elementos **import** y **include** de XSLT. Si esto es **nullptr**, los recursos externos no se resuelven. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const String\&) method


Carga y compila la hoja de estilo ubicada en la URI especificada.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheetUri | const String\& | El URI de la hoja de estilo. |

## Ver también

* Class [String](../../../system/string/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


Carga y compila la hoja de estilo XSLT especificada por el URI. El [XmlResolver](../../../system.xml/xmlresolver/) resuelve cualquier elemento **import** o **include** de XSLT y la configuración de XSLT determina los permisos para la hoja de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheetUri | const String\& | El URI de la hoja de estilo. |
| settings | const SharedPtr\<XsltSettings\>\& | Los [XsltSettings](../../xsltsettings/) a aplicar a la hoja de estilo. Si esto es **nullptr**, se aplica la configuración [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver el URI de la hoja de estilo y cualquier hoja de estilo referenciada en los elementos **import** y **include** de XSLT. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
