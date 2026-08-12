---
title: "Метод System::Xml::XmlWriter::WriteSurrogateCharEntity"
linktitle: "WriteSurrogateCharEntity"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlWriter::WriteSurrogateCharEntity. При переопределении в производном классе генерирует и записывает сущность суррогатного символа для пары суррогатных символов в C++."
type: docs
weight: 3400
url: /ru/cpp/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity method


При переопределении в производном классе генерирует и записывает сущность суррогатного символа для пары суррогатных символов.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| lowChar | char16_t | Нижний суррогат. Должен быть значением от 0xDC00 до 0xDFFF. |
| highChar | char16_t | Верхний суррогат. Должен быть значением от 0xD800 до 0xDBFF. |

## См. также

* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
