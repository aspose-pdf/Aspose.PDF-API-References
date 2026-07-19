---
title: "System::Xml::XmlTextReader::ReadChars метод"
linktitle: "ReadChars"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::ReadChars метод. Считывает текстовое содержимое элемента в буфер символов. Этот метод предназначен для чтения больших потоков встроенного текста путем последовательных вызовов в C++."
type: docs
weight: 4600
url: /ru/cpp/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars method


Считывает текстовое содержимое элемента в буфер символов. Этот метод предназначен для последовательного чтения больших потоков встроенного текста.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<char16_t\>\& | Массив символов, служащий буфером, в который записывается текстовое содержимое. |
| индекс | int32_t | Позиция внутри **buffer**, с которой метод может начать записывать текстовое содержимое. |
| count | int32_t | Количество символов для записи в **buffer**. |

### ReturnValue

Количество считанных символов. Может быть 0, если читатель не находится на элементе или если больше нет текстового содержимого для возврата в текущем контексте.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
