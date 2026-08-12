---
title: "System::Xml::Xsl::IXsltContextFunction::Invoke‑metod"
linktitle: "Invoke"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::IXsltContextFunction::Invoke‑metod. Tillhandahåller metoden för att anropa funktionen med de givna argumenten i den givna kontexten i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke method


Tillhandahåller metoden för att anropa funktionen med de angivna argumenten i den givna kontexten.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xsltContext | SharedPtr\<XsltContext\> | XSLT‑kontexten för funktionsanropet. |
| args | ArrayPtr\<SharedPtr\<Object\>\> | Argumenten för funktionsanropet. Varje argument är ett element i arrayen. |
| docContext | SharedPtr\<System::Xml::XPath::XPathNavigator\> | Kontextnoden för funktionsanropet. |

### ReturnValue

Ett [Object](../../../system/object/)-objekt som representerar funktionens returvärde.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
