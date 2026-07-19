---
title: "System::Xml::XmlReader::ReadContentAsBase64 метод"
linktitle: "ReadContentAsBase64"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadContentAsBase64 метод. Считывает содержимое и возвращает декодированные из Base64 бинарные байты в C++."
type: docs
weight: 4000
url: /ru/cpp/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64 method


Читает содержимое и возвращает двоичные байты, декодированные из Base64.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArrayPtr\<uint8_t\> | Буфер, в который копировать полученный текст. Это значение не может быть **nullptr**. |
| индекс | int32_t | Смещение в буфере, с которого начинать копировать результат. |
| count | int32_t | Максимальное количество байтов для копирования в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### ReturnValue

Количество байтов, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
