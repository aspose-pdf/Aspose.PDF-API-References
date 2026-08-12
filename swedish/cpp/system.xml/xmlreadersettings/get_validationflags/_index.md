---
title: "System::Xml::XmlReaderSettings::get_ValidationFlags‑metod"
linktitle: "get_ValidationFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReaderSettings::get_ValidationFlags‑metod. Returnerar ett värde som anger schemavalideringsinställningarna. Denna inställning gäller för XmlReader‑objekt som validerar scheman (XmlReaderSettings::get_ValidationType‑värdet är ValidationType::Schema) i C++."
type: docs
weight: 1800
url: /sv/cpp/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags method


Returnerar ett värde som anger schemavalideringsinställningarna. Denna inställning gäller för [XmlReader](../../xmlreader/)‑objekt som validerar scheman ([XmlReaderSettings::get_ValidationType](../get_validationtype/)‑värdet är [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### ReturnValue

En bitvis kombination av uppräkningsvärden som specificerar valideringsalternativ. XmlSchemaValidationFlags::ProcessIdentityConstraints och XmlSchemaValidationFlags::AllowXmlAttributes är aktiverade som standard. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation och XmlSchemaValidationFlags::ReportValidationWarnings är inaktiverade som standard.

## Se även

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
