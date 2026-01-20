---
title: System::Xml::Schema::XmlSchemaValidator::ValidateText method
linktitle: ValidateText
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidator::ValidateText method. Validates whether the text string specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content in C++.'
type: docs
weight: 2000
url: /cpp/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) method


Validates whether the text **string** specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | const String\& | A text **string** to validate in the current element context. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateText(XmlValueGetter) method


Validates whether the text returned by the [XmlValueGetter](../../xmlvaluegetter/) object specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | XmlValueGetter | An [XmlValueGetter](../../xmlvaluegetter/) callback used to pass the text value as a type compatible with the XML [Schema](../../) Definition Language (XSD) type of the attribute. |

## See Also

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
