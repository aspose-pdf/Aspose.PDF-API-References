---
title: "System::Xml::XmlReaderSettings::get_ValidationFlags метод"
linktitle: "get_ValidationFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReaderSettings::get_ValidationFlags метод. Возвращает значение, указывающее параметры проверки схемы. Эта настройка применяется к объектам XmlReader, которые проверяют схемы (значение XmlReaderSettings::get_ValidationType равно ValidationType::Schema) в C++."
type: docs
weight: 1800
url: /ru/cpp/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags method


Возвращает значение, указывающее параметры проверки схемы. Эта настройка применяется к объектам [XmlReader](../../xmlreader/), которые проверяют схемы (значение [XmlReaderSettings::get_ValidationType](../get_validationtype/) равно [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### ReturnValue

Битовая комбинация значений перечисления, определяющих параметры проверки. XmlSchemaValidationFlags::ProcessIdentityConstraints и XmlSchemaValidationFlags::AllowXmlAttributes включены по умолчанию. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation и XmlSchemaValidationFlags::ReportValidationWarnings отключены по умолчанию.

## См. также

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
