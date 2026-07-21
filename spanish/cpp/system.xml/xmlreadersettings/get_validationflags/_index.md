---
title: "System::Xml::XmlReaderSettings::get_ValidationFlags método"
linktitle: "get_ValidationFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReaderSettings::get_ValidationFlags método. Devuelve un valor que indica la configuración de validación del esquema. Esta configuración se aplica a los objetos XmlReader que validan esquemas (XmlReaderSettings::get_ValidationType valor es ValidationType::Schema) en C++."
type: docs
weight: 1800
url: /es/cpp/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags method


Devuelve un valor que indica la configuración de validación del esquema. Esta configuración se aplica a los objetos [XmlReader](../../xmlreader/) que validan esquemas ([XmlReaderSettings::get_ValidationType](../get_validationtype/) valor es [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### ReturnValue

Una combinación bit a bit de valores de enumeración que especifican opciones de validación. XmlSchemaValidationFlags::ProcessIdentityConstraints y XmlSchemaValidationFlags::AllowXmlAttributes están habilitados por defecto. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation y XmlSchemaValidationFlags::ReportValidationWarnings están deshabilitados por defecto.

## Ver también

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
