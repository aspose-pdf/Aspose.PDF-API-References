---
title: "System::Xml::XmlValidatingReader::ReadContentAsBase64 method"
linktitle: "ReadContentAsBase64"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::ReadContentAsBase64 method. Считывает содержимое и возвращает двоичные байты, декодированные из Base64, в C++."
type: docs
weight: 4100
url: /ru/cpp/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64 method


Читает содержимое и возвращает двоичные байты, декодированные из Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
