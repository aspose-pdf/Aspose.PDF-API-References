---
title: "System::Xml::XmlValidatingReader::ReadContentAsBinHex метод"
linktitle: "ReadContentAsBinHex"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::ReadContentAsBinHex метод. Считывает содержимое и возвращает двоичные байты, декодированные из BinHex, в C++."
type: docs
weight: 4200
url: /ru/cpp/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex method


Читает содержимое и возвращает двоичные байты, декодированные из BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
