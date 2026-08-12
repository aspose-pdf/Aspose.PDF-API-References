---
title: "Método System::Xml::XmlReader::get_SchemaInfo"
linktitle: "get_SchemaInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReader::get_SchemaInfo. Devuelve la información del esquema que ha sido asignada al nodo actual como resultado de la validación del esquema en C++."
type: docs
weight: 2200
url: /es/cpp/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo method


Devuelve la información del esquema que ha sido asignada al nodo actual como resultado de la validación del esquema.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### ReturnValue

Un objeto IXmlSchemaInfo que contiene la información del esquema para el nodo actual. La información de [Schema](../../../system.xml.schema/) puede establecerse en elementos, atributos o en nodos de texto con un valor no nulo de [XmlReader::get_ValueType](../get_valuetype/). Si el nodo actual no es uno de los tipos de nodo anteriores, o si la instancia de [XmlReader](../) no informa información del esquema, este método devuelve **nullptr**. Si este método se llama desde un objeto [XmlTextReader](../../xmltextreader/) o [XmlValidatingReader](../../xmlvalidatingreader/), siempre devuelve **nullptr**. Estas implementaciones de [XmlReader](../) no exponen información del esquema a través del método get_SchemaInfo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
