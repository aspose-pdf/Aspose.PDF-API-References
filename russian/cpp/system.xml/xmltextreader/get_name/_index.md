---
title: "System::Xml::XmlTextReader::get_Name метод"
linktitle: "get_Name"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::get_Name метод. Возвращает квалифицированное имя текущего узла в C++."
type: docs
weight: 1900
url: /ru/cpp/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name method


Возвращает квалифицированное имя текущего узла.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### ReturnValue

Квалифицированное имя текущего узла. Например, **Name** — **bk:book** для элемента **<bk:book>**.
## Примечания



Возвращаемое имя зависит от значения [XmlTextReader::get_NodeType](../get_nodetype/) узла. Следующие типы узлов возвращают указанные значения. Все остальные типы узлов возвращают пустую строку. |||
|-|-|
| Тип узла | Имя |
| Атрибут | Имя атрибута. |
| DocumentType | Имя типа документа. |
| Элемент | Имя тега. |
| EntityReference | Имя ссылки на сущность. |
| ProcessingInstruction | Цель инструкции обработки. |
| XmlDeclaration | Буквальная строка xml. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
