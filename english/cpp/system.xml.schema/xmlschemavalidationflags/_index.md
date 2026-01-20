---
title: System::Xml::Schema::XmlSchemaValidationFlags enum
linktitle: XmlSchemaValidationFlags
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidationFlags enum. Specifies schema validation options used by the XmlSchemaValidator and XmlReader classes in C++.'
type: docs
weight: 7900
url: /cpp/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum


Specifies schema validation options used by the [XmlSchemaValidator](../xmlschemavalidator/) and [XmlReader](../../system.xml/xmlreader/) classes.

```cpp
enum class XmlSchemaValidationFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Do not process identity constraints, inline schemas, schema location hints, or report schema validation warnings. |
| ProcessInlineSchema | 1 | Process inline schemas encountered during validation. |
| ProcessSchemaLocation | 2 | Process schema location hints (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) encountered during validation. |
| ReportValidationWarnings | 4 | Report schema validation warnings encountered during validation. |
| ProcessIdentityConstraints | 8 | Process identity constraints (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) encountered during validation. |
| AllowXmlAttributes | 16 | Allow xml:* attributes even if they are not defined in the schema. The attributes will be validated based on their data type. |

## See Also

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
