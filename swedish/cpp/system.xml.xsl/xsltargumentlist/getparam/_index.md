---
title: "System::Xml::Xsl::XsltArgumentList::GetParam metod"
linktitle: "GetParam"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltArgumentList::GetParam metod. Returnerar parametern som är associerad med det namnrymdskvalificerade namnet i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam method


Returnerar parametern som är associerad med det namnrymdskvalificerade namnet.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const String\& | Namnet på parametern. [XsltArgumentList](../) kontrollerar inte att det angivna namnet är ett giltigt lokalt namn; dock kan inte namnet vara **nullptr**. |
| namespaceUri | const String\& | Den namnrymds-URI som är associerad med parametern. |

### ReturnValue

Parameterobjektet eller **nullptr** om det inte hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
