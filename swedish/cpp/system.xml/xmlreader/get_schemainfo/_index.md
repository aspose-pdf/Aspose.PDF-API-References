---
title: "System::Xml::XmlReader::get_SchemaInfo metod"
linktitle: "get_SchemaInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::get_SchemaInfo metod. Returnerar schemainformationen som har tilldelats den aktuella noden som ett resultat av schemavalidering i C++."
type: docs
weight: 2200
url: /sv/cpp/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo method


Returnerar schemainformationen som har tilldelats den aktuella noden som ett resultat av schemavalidering.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### ReturnValue

Ett IXmlSchemaInfo-objekt som innehåller schemainformationen för den aktuella noden. [Schema](../../../system.xml.schema/) information kan sättas på element, attribut eller på textnoder med ett icke‑null [XmlReader::get_ValueType](../get_valuetype/) värde. Om den aktuella noden inte är någon av ovanstående nodtyper, eller om [XmlReader](../)‑instansen inte rapporterar schemainformation, returnerar den här metoden **nullptr**. Om den här metoden anropas från ett [XmlTextReader](../../xmltextreader/)‑ eller ett [XmlValidatingReader](../../xmlvalidatingreader/)‑objekt, returnerar den alltid **nullptr**. Dessa [XmlReader](../)‑implementationer exponerar inte schemainformation via get_SchemaInfo‑metoden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
