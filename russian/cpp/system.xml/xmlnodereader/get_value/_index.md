---
title: "Метод System::Xml::XmlNodeReader::get_Value"
linktitle: "get_Value"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlNodeReader::get_Value. Возвращает текстовое значение текущего узла в C++."
type: docs
weight: 2100
url: /ru/cpp/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value method


Возвращает текстовое значение текущего узла.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### ReturnValue

Возвращаемое значение зависит от [XmlNodeReader::get_NodeType](../get_nodetype/) узла.
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
