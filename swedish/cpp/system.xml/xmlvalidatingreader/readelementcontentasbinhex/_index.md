---
title: "System::Xml::XmlValidatingReader::ReadElementContentAsBinHex metod"
linktitle: "ReadElementContentAsBinHex"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader::ReadElementContentAsBinHex metod. Läser elementet och avkodar BinHex-innehållet i C++."
type: docs
weight: 4400
url: /sv/cpp/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex method


Läser elementet och avkodar BinHex-innehållet.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
