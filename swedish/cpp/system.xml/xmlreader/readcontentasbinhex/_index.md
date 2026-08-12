---
title: "System::Xml::XmlReader::ReadContentAsBinHex‑metod"
linktitle: "ReadContentAsBinHex"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadContentAsBinHex‑metod. Läser innehållet och returnerar de BinHex‑avkodade binära bytena i C++."
type: docs
weight: 4100
url: /sv/cpp/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex method


Läser innehållet och returnerar de **BinHex**‑avkodade binära byten.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
