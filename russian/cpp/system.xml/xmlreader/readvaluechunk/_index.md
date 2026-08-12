---
title: "System::Xml::XmlReader::ReadValueChunk метод"
linktitle: "ReadValueChunk"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadValueChunk метод. Читает большие потоки текста, встроенные в XML‑документ, в C++."
type: docs
weight: 7400
url: /ru/cpp/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk method


Считывает большие потоки текста, встроенные в XML‑документ.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArrayPtr\<char16_t\> | Массив символов, который служит буфером, в который записывается текстовое содержимое. Это значение не может быть **nullptr**. |
| index | int32_t | Смещение в буфере, с которого [XmlReader](../) может начать копировать результаты. |
| count | int32_t | Максимальное количество символов для копирования в буфер. Фактическое количество скопированных символов возвращается этим методом. |

### ReturnValue

Количество символов, считанных в буфер. При отсутствии дальнейшего текстового содержимого возвращается значение ноль.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
