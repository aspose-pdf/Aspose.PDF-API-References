---
title: "System::Xml::Schema::XmlSeverityType enum"
linktitle: "XmlSeverityType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSeverityType enum. Представляет степень серьезности события проверки в C++."
type: docs
weight: 8100
url: /ru/cpp/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum


Представляет степень важности события проверки.

```cpp
enum class XmlSeverityType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Error | 0 | Указывает, что при проверке экземпляра документа произошла ошибка проверки. Это относится к определениям типов документов (DTDs) и схемам XML [Schema](../) (язык определения XSD). Ограничения валидности World Wide [Web](../../system.web/) Consortium (W3C) рассматриваются как ошибки. Если обработчик события проверки не был создан, ошибки вызывают исключение. |
| Warning | 1 | Указывает, что событие проверки произошло, но не является ошибкой. Предупреждение обычно выдаётся, когда отсутствует DTD или XML [Schema](../) для проверки конкретного элемента или атрибута. В отличие от ошибок, предупреждения не вызывают исключение, если обработчик события проверки отсутствует. |

## См. также

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
