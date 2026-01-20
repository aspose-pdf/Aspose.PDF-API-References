---
title: System::Xml::Xsl::XslCompiledTransform::Load method
linktitle: Load
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XslCompiledTransform::Load method. Compiles the style sheet contained in the IXPathNavigable object in C++.'
type: docs
weight: 300
url: /cpp/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Compiles the style sheet contained in the IXPathNavigable object.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the style sheet. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) method


Compiles the XSLT style sheet contained in the IXPathNavigable. The [XmlResolver](../../../system.xml/xmlresolver/) resolves any XSLT **import** or **include** elements and the XSLT settings determine the permissions for the style sheet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the style sheet. |
| settings | SharedPtr\<XsltSettings\> | The [XsltSettings](../../xsltsettings/) to apply to the style sheet. If this is **nullptr**, the [XsltSettings::get_Default](../../xsltsettings/get_default/) setting is applied. |
| stylesheetResolver | SharedPtr\<XmlResolver\> | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve any style sheets referenced in XSLT **import** and **include** elements. If this is **nullptr**, external resources are not resolved. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) method


Compiles the style sheet contained in the [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the style sheet. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


Compiles the XSLT style sheet contained in the [XmlReader](../../../system.xml/xmlreader/). The [XmlResolver](../../../system.xml/xmlresolver/) resolves any XSLT **import** or **include** elements and the XSLT settings determine the permissions for the style sheet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | The [XmlReader](../../../system.xml/xmlreader/) containing the style sheet. |
| settings | const SharedPtr\<XsltSettings\>\& | The [XsltSettings](../../xsltsettings/) to apply to the style sheet. If this is **nullptr**, the [XsltSettings::get_Default](../../xsltsettings/get_default/) setting is applied. |
| stylesheetResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve any style sheets referenced in XSLT **import** and **include** elements. If this is **nullptr**, external resources are not resolved. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const String\&) method


Loads and compiles the style sheet located at the specified URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stylesheetUri | const String\& | The URI of the style sheet. |

## See Also

* Class [String](../../../system/string/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


Loads and compiles the XSLT style sheet specified by the URI. The [XmlResolver](../../../system.xml/xmlresolver/) resolves any XSLT **import** or **include** elements and the XSLT settings determine the permissions for the style sheet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stylesheetUri | const String\& | The URI of the style sheet. |
| settings | const SharedPtr\<XsltSettings\>\& | The [XsltSettings](../../xsltsettings/) to apply to the style sheet. If this is **nullptr**, the [XsltSettings::get_Default](../../xsltsettings/get_default/) setting is applied. |
| stylesheetResolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the style sheet URI and any style sheets referenced in XSLT **import** and **include** elements. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslCompiledTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
