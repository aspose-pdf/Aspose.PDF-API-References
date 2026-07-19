---
title: "Метод Aspose::Pdf::Text::FontCollection::Contains"
linktitle: "Contains"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Text::FontCollection::Contains. Определяет, содержит ли коллекция определённое значение в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.text/fontcollection/contains/
---
## FontCollection::Contains(const System::SharedPtr\<Font\>\&) const method


Определяет, содержит ли коллекция определённое значение.

```cpp
bool Aspose::Pdf::Text::FontCollection::Contains(const System::SharedPtr<Font> &item) const override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const System::SharedPtr\<Font\>\& | Объект, который нужно найти в коллекции |

### ReturnValue

true, если элемент найден в коллекции; иначе — false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontCollection::Contains(const System::String\&) const method


Проверяет, существует ли шрифт в коллекции шрифтов.

```cpp
bool Aspose::Pdf::Text::FontCollection::Contains(const System::String &name) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const System::String\& | [Font](../../font/) имя. |

### ReturnValue

True, если коллекция содержит шрифт с указанным именем.

## См. также

* Class [String](../../../system/string/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
