---
title: "Перечисление System::Xml::ValidationType"
linktitle: "ValidationType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Xml::ValidationType. Задает тип проверки, которую следует выполнить в C++."
type: docs
weight: 5500
url: /ru/cpp/system.xml/validationtype/
---
## ValidationType enum


Указывает тип выполняемой проверки.

```cpp
enum class ValidationType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Проверка не выполняется, и ошибки проверки не генерируются. Эта настройка создает парсер, совместимый с XML 1.0, без валидации. |
| Auto | 1 | Проверяет наличие информации DTD или схемы. |
| DTD | 2 | Проверяет в соответствии с DTD. |
| XDR | 3 | Проверка в соответствии со схемами XML-Data Reduced (XDR), включая встроенные схемы XDR. Схемы XDR распознаются с использованием префикса пространства имён **x-schema** или значения [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Проверка в соответствии с языком определения XML [Schema](../../system.xml.schema/) (XSD), включая встроенные XML-схемы. XML-схемы связываются с URI пространств имён либо с помощью атрибута **schemaLocation**, либо с предоставленными **Schemas**. |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
