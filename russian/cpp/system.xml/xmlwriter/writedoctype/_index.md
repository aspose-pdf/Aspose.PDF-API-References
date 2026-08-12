---
title: "System::Xml::XmlWriter::WriteDocType метод"
linktitle: "WriteDocType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::WriteDocType метод. При переопределении в производном классе записывает объявление DOCTYPE с указанным именем и необязательными атрибутами в C++."
type: docs
weight: 1700
url: /ru/cpp/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType method


При переопределении в производном классе записывает объявление DOCTYPE с указанным именем и необязательными атрибутами.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const String\& | Имя DOCTYPE. Оно должно быть непустым. |
| pubid | const String\& | Если не равно null, также записывает PUBLIC "pubid" "sysid", где **pubid** и **sysid** заменяются значением переданных аргументов. |
| sysid | const String\& | Если **pubid** равен **nullptr** и **sysid** не равен null, он записывает SYSTEM \"sysid\", где **sysid** заменяется значением этого аргумента. |
| subset | const String\& | Если не null, он записывает [subset], где subset заменяется значением этого аргумента. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
