---
title: "System::Xml::XmlNodeReader::get_Name метод"
linktitle: "get_Name"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeReader::get_Name метод. Возвращает квалифицированное имя текущего узла в C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name method


Возвращает квалифицированное имя текущего узла.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### ReturnValue

Квалифицированное имя текущего узла. Например, **Name** — **bk:book** для элемента **<bk:book>**.
## Примечания



Возвращаемое имя зависит от значения [XmlNodeReader::get_NodeType](../get_nodetype/) узла. Следующие типы узлов возвращают указанные значения. Все остальные типы узлов возвращают пустую строку. |||
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
