---
title: System::Xml::ValidationType enum
linktitle: ValidationType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::ValidationType enum. Specifies the type of validation to perform in C++.'
type: docs
weight: 5500
url: /cpp/system.xml/validationtype/
---
## ValidationType enum


Specifies the type of validation to perform.

```cpp
enum class ValidationType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No validation is performed, and no validation errors are thrown. This setting creates an XML 1.0 compliant non-validating parser. |
| Auto | 1 | Validates if DTD or schema information is found. |
| DTD | 2 | Validates according to the DTD. |
| XDR | 3 | Validate according to XML-Data Reduced (XDR) schemas, including inline XDR schemas. XDR schemas are recognized using the **x-schema** namespace prefix or the [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) value. |
| Schema | 4 | Validate according to XML [Schema](../../system.xml.schema/) definition language (XSD) schemas, including inline XML Schemas. XML Schemas are associated with namespace URIs either by using the **schemaLocation** attribute or the provided **Schemas**. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
