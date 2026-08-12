---
title: "System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes metod"
linktitle: "GetUnspecifiedDefaultAttributes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes metod. Validerar identitetsbegränsningar på standardattributen och fyller den angivna Listan med XmlSchemaAttribute-objekt för alla attribut med standardvärden som ännu inte har validerats med XmlSchemaValidator::ValidateAttribute‑metoden i elementkontexten i C++."
type: docs
weight: 900
url: /sv/cpp/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes method


Validerar identitetsbegränsningar på standardattributen och fyller den angivna Listan med [XmlSchemaAttribute](../../xmlschemaattribute/)‑objekt för alla attribut med standardvärden som ännu inte har validerats med [XmlSchemaValidator::ValidateAttribute](../validateattribute/)‑metoden i elementkontexten.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| defaultAttributes | const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\& | En Lista att fylla med [XmlSchemaAttribute](../../xmlschemaattribute/)‑objekt för alla attribut som ännu inte har påträffats under validering i elementkontexten. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
