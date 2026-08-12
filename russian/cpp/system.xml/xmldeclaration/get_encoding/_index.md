---
title: "System::Xml::XmlDeclaration::get_Encoding метод"
linktitle: "get_Encoding"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDeclaration::get_Encoding метод. Возвращает уровень кодировки XML‑документа в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding method


Возвращает уровень кодировки XML‑документа.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### ReturnValue

Допустимое имя кодировки символов.
## Примечания



Наиболее часто поддерживаемые имена кодировок символов для XML перечислены ниже: |||
|-|-|
| Категория | Имена кодировок |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (где "n" — цифра от 1 до 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Это значение является необязательным. Если значение не задано, этот метод возвращает [String::Empty](../../../system/string/empty/). Если атрибут кодировки не включён, предполагается кодировка UTF-8 при записи или сохранении документа.
## См. также

* Class [String](../../../system/string/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
