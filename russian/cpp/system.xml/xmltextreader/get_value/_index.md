---
title: "System::Xml::XmlTextReader::get_Value метод"
linktitle: "get_Value"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::get_Value метод. Возвращает текстовое значение текущего узла в C++."
type: docs
weight: 2900
url: /ru/cpp/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value method


Возвращает текстовое значение текущего узла.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### ReturnValue

Возвращаемое значение зависит от значения [XmlTextReader::get_NodeType](../get_nodetype/) узла.
## Примечания



В следующей таблице перечислены типы узлов, имеющие значение для возврата. Все остальные типы узлов возвращают [String::Empty](../../../system/string/empty/). |||
|-|-|
| Тип узла | Значение |
| Атрибут | Значение атрибута. |
| CDATA | Содержимое секции CDATA. |
| Comment | Содержимое комментария. |
| DocumentType | Внутреннее подмножество. |
| ProcessingInstruction | Всё содержимое, за исключением цели. |
| SignificantWhitespace | Пробельные символы внутри области xml:space='preserve'. |
| Text | Содержимое текстового узла. |
| Whitespace | Пробельные символы между разметкой. |
| XmlDeclaration | Содержимое декларации. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
