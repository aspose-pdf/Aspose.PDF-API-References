---
title: System::Xml::Schema::XmlSchemaCollection::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaCollection::idx_get method. Returns the XmlSchema associated with the given namespace URI in C++.'
type: docs
weight: 800
url: /cpp/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get method


Returns the [XmlSchema](../../xmlschema/) associated with the given namespace URI.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | const String\& | The namespace URI associated with the schema you want to return. This will typically be the **targetNamespace** of the schema. |

### ReturnValue

The [XmlSchema](../../xmlschema/) associated with the namespace URI; **nullptr** if there is no loaded schema associated with the given namespace or if the namespace is associated with an XDR schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
