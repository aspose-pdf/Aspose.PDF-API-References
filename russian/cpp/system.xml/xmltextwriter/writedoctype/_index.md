---
title: "System::Xml::XmlTextWriter::WriteDocType метод"
linktitle: "WriteDocType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextWriter::WriteDocType метод. Записывает объявление DOCTYPE с указанным именем и необязательными атрибутами в C++."
type: docs
weight: 2500
url: /ru/cpp/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType method


Записывает объявление DOCTYPE с указанным именем и необязательными атрибутами.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const String\& | Имя DOCTYPE. Оно должно быть непустым. |
| pubid | const String\& | Если не равно null, также записывает PUBLIC "pubid" "sysid", где **pubid** и **sysid** заменяются значением переданных аргументов. |
| sysid | const String\& | Если **pubid** равно null, а **sysid** не null, он записывает SYSTEM "sysid", где **sysid** заменяется значением этого аргумента. |
| subset | const String\& | Если не null, он записывает [subset], где subset заменяется значением этого аргумента. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
