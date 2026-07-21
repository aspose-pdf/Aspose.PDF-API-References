---
title: "System::Xml::Schema::XmlSchemaCollection::idx_get método"
linktitle: "idx_get"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaCollection::idx_get método. Devuelve el XmlSchema asociado con el URI de espacio de nombres proporcionado en C++."
type: docs
weight: 800
url: /es/cpp/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get method


Devuelve el [XmlSchema](../../xmlschema/) asociado con el URI de espacio de nombres proporcionado.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const String\& | El URI de espacio de nombres asociado con el esquema que desea devolver. Normalmente será el **targetNamespace** del esquema. |

### ReturnValue

El [XmlSchema](../../xmlschema/) asociado con el URI de espacio de nombres; **nullptr** si no hay ningún esquema cargado asociado con el espacio de nombres proporcionado o si el espacio de nombres está asociado con un esquema XDR.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
