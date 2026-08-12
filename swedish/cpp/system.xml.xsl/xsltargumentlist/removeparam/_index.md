---
title: "System::Xml::Xsl::XsltArgumentList::RemoveParam metod"
linktitle: "RemoveParam"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltArgumentList::RemoveParam metod. Tar bort parametern från XsltArgumentList i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam method


Tar bort parametern från [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const String\& | Namnet på parametern som ska tas bort. [XsltArgumentList](../) kontrollerar inte att det angivna namnet är ett giltigt lokalt namn; dock kan inte namnet vara **nullptr**. |
| namespaceUri | const String\& | Namnrymds-URI för parametern som ska tas bort. |

### ReturnValue

Parameterobjektet eller **nullptr** om det inte hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
