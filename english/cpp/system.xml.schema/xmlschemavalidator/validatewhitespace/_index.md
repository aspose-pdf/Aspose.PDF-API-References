---
title: System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace method
linktitle: ValidateWhitespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace method. Validates whether the white space in the string specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content in C++.'
type: docs
weight: 2100
url: /cpp/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) method


Validates whether the white space in the **string** specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | const String\& | A white space **string** to validate in the current element context. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) method


Validates whether the white space returned by the [XmlValueGetter](../../xmlvaluegetter/) object specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | XmlValueGetter | An [XmlValueGetter](../../xmlvaluegetter/) callback used to pass the white space value as a type compatible with the XML [Schema](../../) Definition Language (XSD) type of the attribute. |

## See Also

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
