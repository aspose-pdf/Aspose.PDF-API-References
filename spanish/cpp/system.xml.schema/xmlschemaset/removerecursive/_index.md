---
title: "System::Xml::Schema::XmlSchemaSet::RemoveRecursive método"
linktitle: "RemoveRecursive"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSet::RemoveRecursive método. Elimina el esquema especificado del lenguaje de definición de XML Schema (XSD) y todos los esquemas que importa del XmlSchemaSet en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive method


Elimina el esquema especificado del lenguaje de definición de XML [Schema](../../) (XSD) y todos los esquemas que importa del [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemaToRemove | const SharedPtr\<XmlSchema\>\& | El objeto [XmlSchema](../../xmlschema/) a eliminar del [XmlSchemaSet](../). |

### ReturnValue

**true** if the [XmlSchema](../../xmlschema/) object and all its imports were successfully removed; otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
