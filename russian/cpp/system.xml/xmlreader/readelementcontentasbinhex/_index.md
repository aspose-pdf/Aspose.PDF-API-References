---
title: "System::Xml::XmlReader::ReadElementContentAsBinHex метод"
linktitle: "ReadElementContentAsBinHex"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadElementContentAsBinHex метод. Считывает элемент и декодирует содержимое BinHex в C++."
type: docs
weight: 5400
url: /ru/cpp/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex method


Считывает элемент и декодирует содержимое **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
