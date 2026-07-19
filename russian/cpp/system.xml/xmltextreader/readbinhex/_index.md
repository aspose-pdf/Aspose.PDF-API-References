---
title: "System::Xml::XmlTextReader::ReadBinHex метод"
linktitle: "ReadBinHex"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::ReadBinHex метод. Декодирует BinHex и возвращает декодированные бинарные байты в C++."
type: docs
weight: 4500
url: /ru/cpp/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex method


Декодирует **BinHex** и возвращает декодированные двоичные байты.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const ArrayPtr\<uint8_t\>\& | Массив байтов, который служит буфером, в который записываются декодированные бинарные байты. |
| смещение | int32_t | Нулевой индекс в массиве, указывающий, где метод может начать запись в буфер. |
| len | int32_t | Количество байтов для записи в буфер. |

### ReturnValue

Количество байтов, записанных в ваш буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
