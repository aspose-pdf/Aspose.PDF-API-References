---
title: "System::Xml::XmlTextReader::ReadBase64 метод"
linktitle: "ReadBase64"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::ReadBase64 метод. Декодирует Base64 и возвращает декодированные двоичные байты в C++."
type: docs
weight: 4400
url: /ru/cpp/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64 method


Декодирует Base64 и возвращает декодированные двоичные байты.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const ArrayPtr\<uint8_t\>\& | Массив символов, служащий буфером, в который записывается текстовое содержимое. |
| смещение | int32_t | Нулевой индекс в массиве, указывающий, где метод может начать запись в буфер. |
| len | int32_t | Количество байтов для записи в буфер. |

### ReturnValue

Количество байтов, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
