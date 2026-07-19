---
title: "Метод System::Xml::XmlTextReader::ReadContentAsBinHex"
linktitle: "ReadContentAsBinHex"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlTextReader::ReadContentAsBinHex. Считывает содержимое и возвращает бинарные байты, декодированные из BinHex, в C++."
type: docs
weight: 4800
url: /ru/cpp/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex method


Считывает содержимое и возвращает декодированные из **BinHex** двоичные байты.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
