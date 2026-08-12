---
title: "System::Xml::Schema::XmlSchemaCollection::idx_get metod"
linktitle: "idx_get"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaCollection::idx_get metod. Returnerar XmlSchema som är associerad med den angivna namnrymds-URI:n i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get method


Returnerar [XmlSchema](../../xmlschema/) som är associerad med den angivna namnrymds-URI:n.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const String\& | Namnrums-URI:n som är associerad med schemat du vill returnera. Detta kommer vanligtvis att vara **targetNamespace** för schemat. |

### ReturnValue

Den [XmlSchema](../../xmlschema/) som är associerad med namnrymds-URI:n; **nullptr** om det inte finns något laddat schema associerat med den angivna namnrymden eller om namnrymden är associerad med ett XDR-schema.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
