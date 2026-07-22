---
title: "System::Xml::XmlNodeReader::ReadElementContentAsBase64‑metod"
linktitle: "ReadElementContentAsBase64"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::ReadElementContentAsBase64‑metod. Läser elementet och avkodar Base64‑innehållet i C++."
type: docs
weight: 3400
url: /sv/cpp/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64 method


Läser elementet och avkodar Base64-innehållet.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | ArrayPtr\<uint8_t\> | Bufferten som texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | int32_t | Offseten i bufferten där kopieringen av resultatet ska börja. |
| count | int32_t | Det maximala antalet byte att kopiera till bufferten. Det faktiska antalet kopierade byte returneras från den här metoden. |

### ReturnValue

Antalet byte som skrivs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
