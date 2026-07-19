---
title: "System::Xml::XmlReader::get_Value метод"
linktitle: "get_Value"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::get_Value метод. При переопределении в производном классе возвращает текстовое значение текущего узла в C++."
type: docs
weight: 2400
url: /ru/cpp/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value method


При переопределении в производном классе возвращает текстовое значение текущего узла.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### ReturnValue

Возвращаемое значение зависит от значения [XmlReader::get_NodeType](../get_nodetype/) узла.
## Примечания



В следующей таблице перечислены типы узлов, имеющие значение для возврата. Все остальные типы узлов возвращают [String::Empty](../../../system/string/empty/). |||
|-|-|
| Тип узла | Значение |
| Атрибут | Значение атрибута. |
| CDATA | Содержимое секции CDATA. |
| Comment | Содержимое комментария. |
| DocumentType | Внутреннее подмножество. |
| ProcessingInstruction | Всё содержимое, за исключением цели. |
| SignificantWhitespace | Пробельные символы между разметкой в модели смешанного содержимого. |
| Text | Содержимое текстового узла. |
| Whitespace | Пробельные символы между разметкой. |
| XmlDeclaration | Содержимое декларации. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
