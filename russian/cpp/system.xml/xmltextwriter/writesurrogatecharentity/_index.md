---
title: "System::Xml::XmlTextWriter::WriteSurrogateCharEntity метод"
linktitle: "WriteSurrogateCharEntity"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextWriter::WriteSurrogateCharEntity метод. Генерирует и записывает сущность суррогатного символа для пары суррогатных символов в C++."
type: docs
weight: 4000
url: /ru/cpp/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity method


Генерирует и записывает сущность суррогатного символа для пары суррогатных символов.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| lowChar | char16_t | Нижний суррогат. Должен быть значением между **0xDC00** и **0xDFFF**. |
| highChar | char16_t | Верхний суррогат. Должен быть значением между **0xD800** и **0xDBFF**. |

## См. также

* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
