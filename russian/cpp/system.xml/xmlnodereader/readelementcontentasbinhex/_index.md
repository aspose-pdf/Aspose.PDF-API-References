---
title: "System::Xml::XmlNodeReader::ReadElementContentAsBinHex метод"
linktitle: "ReadElementContentAsBinHex"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeReader::ReadElementContentAsBinHex метод. Считывает элемент и декодирует содержимое BinHex в C++."
type: docs
weight: 3500
url: /ru/cpp/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex method


Читает элемент и декодирует содержимое BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
