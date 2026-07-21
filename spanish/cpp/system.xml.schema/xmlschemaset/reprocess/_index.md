---
title: "System::Xml::Schema::XmlSchemaSet::Reprocess method"
linktitle: "Reprocesar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSet::Reprocess method. Reprocesa un esquema del lenguaje de definición de XML Schema (XSD) que ya existe en el XmlSchemaSet en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess method


Reprocesa un esquema del lenguaje de definición de XML [Schema](../../) (XSD) que ya existe en el [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| esquema | SharedPtr\<XmlSchema\> | El esquema a reprocesar. |

### ReturnValue

Un objeto [XmlSchema](../../xmlschema/) si el esquema es un esquema válido. Si el esquema no es válido y se especifica un [ValidationEventHandler](../../validationeventhandler/), se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una [XmlSchemaException](../../xmlschemaexception/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
