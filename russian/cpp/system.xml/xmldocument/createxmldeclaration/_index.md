---
title: "System::Xml::XmlDocument::CreateXmlDeclaration метод"
linktitle: "CreateXmlDeclaration"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDocument::CreateXmlDeclaration метод. Создает узел XmlDeclaration с указанными значениями в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration method


Создает узел [XmlDeclaration](../../xmldeclaration/) с указанными значениями.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| версия | const String\& | Версия должна быть "1.0". |
| encoding | const String\& | Значение атрибута encoding. Это кодировка, которая используется при сохранении [XmlDocument](../) в файл или поток; поэтому её необходимо установить в строку, поддерживаемую классом [Text::Encoding](../../../system.text/encoding/), иначе вызов "XmlDocument::Save(String)" завершится ошибкой. Если значение равно **nullptr** или [String::Empty](../../../system/string/empty/), метод [XmlDocument::Save](../save/) не записывает атрибут encoding в объявление XML, и поэтому используется кодировка по умолчанию UTF-8. |
| standalone | const String\& | Значение должно быть либо "yes", либо "no". Если оно равно **nullptr** или [String::Empty](../../../system/string/empty/), метод [XmlDocument::Save](../save/) не записывает атрибут standalone в объявление XML. |

### ReturnValue

Новый узел [XmlDeclaration](../../xmldeclaration/).
## Примечания



Примечание: Если [XmlDocument](../) сохраняется в TextWriter или [XmlTextWriter](../../xmltextwriter/), значение этой кодировки отбрасывается. Вместо этого используется кодировка TextWriter или [XmlTextWriter](../../xmltextwriter/). Это гарантирует, что записанный XML можно будет прочитать с правильной кодировкой.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
