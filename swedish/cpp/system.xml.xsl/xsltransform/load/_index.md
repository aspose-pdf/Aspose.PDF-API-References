---
title: "System::Xml::Xsl::XslTransform::Load metod"
linktitle: "SharedPtr\\<IO::Stream\\>"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XslTransform::Load metod. Laddar XSLT‑stilmallen som finns i IXPathNavigable i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Laddar XSLT-stilarket som finns i IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Ett objekt som implementerar IXPathNavigable‑gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis ett [XmlDocument](../../../system.xml/xmldocument/)), eller ett XPathDocument som innehåller XSLT‑stilmallen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Laddar XSLT-stilarket som finns i IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | Ett objekt som implementerar IXPathNavigable‑gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis ett [XmlDocument](../../../system.xml/xmldocument/)), eller ett XPathDocument som innehåller XSLT‑stilmallen. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att ladda alla stilmallar som refereras i **xsl:import**‑ och **xsl:include**‑element. Om detta är **nullptr** löses externa resurser inte upp. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


Laddar XSLT-stilarket som finns i XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stilmall | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Ett XPathNavigator‑objekt som innehåller XSLT‑stilmallen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Laddar XSLT-stilarket som finns i XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stilmall | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | Ett XPathNavigator‑objekt som innehåller XSLT‑stilmallen. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att ladda alla stilmallar som refereras i **xsl:import**‑ och **xsl:include**‑element. Om detta är **nullptr** löses externa resurser inte upp. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


Laddar XSLT‑stilmallen som finns i [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)‑objekt som innehåller XSLT‑stilmallen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Laddar XSLT‑stilmallen som finns i [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)‑objekt som innehåller XSLT‑stilmallen. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att ladda alla stilmallar som refereras i **xsl:import**‑ och **xsl:include**‑element. Om detta är **nullptr** löses externa resurser inte upp. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const String\&) method


Laddar XSLT-stilarket som anges av en URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL‑en som specificerar XSLT‑stilmallen att ladda. |

## Se även

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Laddar XSLT-stilarket som anges av en URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL‑en som specificerar XSLT‑stilmallen att ladda. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som ska användas för att ladda stilmallen och eventuella stilmallar som refereras i **xsl:import**‑ och **xsl:include**‑element. Om detta är **nullptr** används en standard‑[XmlUrlResolver](../../../system.xml/xmlurlresolver/) utan användaruppgifter för att öppna stilmallen. Standard‑[XmlUrlResolver](../../../system.xml/xmlurlresolver/) används inte för att lösa några externa resurser i stilmallen, så **xsl:import**‑ och **xsl:include**‑element lösts inte. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
