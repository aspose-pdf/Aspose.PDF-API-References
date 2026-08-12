---
title: "System::Xml::Schema::XmlSchemaValidationFlags перечисление"
linktitle: "XmlSchemaValidationFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaValidationFlags перечисление. Указывает параметры проверки схемы, используемые классами XmlSchemaValidator и XmlReader в C++."
type: docs
weight: 7900
url: /ru/cpp/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum


Указывает параметры проверки схемы, используемые классами [XmlSchemaValidator](../xmlschemavalidator/) и [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Не обрабатывать ограничения идентичности, встроенные схемы, подсказки о расположении схемы или сообщать о предупреждениях проверки схемы. |
| ProcessInlineSchema | 1 | Обрабатывать встроенные схемы, обнаруженные во время проверки. |
| ProcessSchemaLocation | 2 | Обрабатывать подсказки о расположении схем (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**), обнаруженные во время проверки. |
| ReportValidationWarnings | 4 | Сообщать о предупреждениях проверки схем, обнаруженных во время проверки. |
| ProcessIdentityConstraints | 8 | Обрабатывать ограничения идентичности (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**), обнаруженные во время проверки. |
| AllowXmlAttributes | 16 | Разрешать атрибуты xml:* даже если они не определены в схеме. Атрибуты будут проверяться на основе их типа данных. |

## См. также

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
