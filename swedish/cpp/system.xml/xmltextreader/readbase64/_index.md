---
title: "System::Xml::XmlTextReader::ReadBase64 metod"
linktitle: "ReadBase64"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader::ReadBase64 metod. Avkodar Base64 och returnerar de avkodade binära bytena i C++."
type: docs
weight: 4400
url: /sv/cpp/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64 method


Avkodar Base64 och returnerar de avkodade binära byten.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const ArrayPtr\<uint8_t\>\& | Den teckenarray som fungerar som bufferten som textinnehållet skrivs till. |
| förskjutning | int32_t | Det nollbaserade indexet i arrayen som anger var metoden kan börja skriva till bufferten. |
| len | int32_t | Antalet byte som ska skrivas till bufferten. |

### ReturnValue

Antalet byte som skrivs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
