---
title: "Перечисление System::Xml::NewLineHandling"
linktitle: "NewLineHandling"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Xml::NewLineHandling. Указывает, как обрабатывать разрывы строк в C++."
type: docs
weight: 5200
url: /ru/cpp/system.xml/newlinehandling/
---
## NewLineHandling enum


Указывает, как обрабатывать разрывы строк.

```cpp
enum class NewLineHandling
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Replace | 0 | Символы новой строки заменяются, чтобы соответствовать символу, указанному в значении [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Символы новой строки преобразуются в сущности. Эта настройка сохраняет все символы, когда вывод читается нормализующим [XmlReader](../xmlreader/). |
| None | 2 | Символы новой строки остаются неизменными. Вывод совпадает с вводом. |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
