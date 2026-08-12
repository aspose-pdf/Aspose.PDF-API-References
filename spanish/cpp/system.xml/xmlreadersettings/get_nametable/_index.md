---
title: "Método System::Xml::XmlReaderSettings::get_NameTable"
linktitle: "get_NameTable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReaderSettings::get_NameTable. Devuelve el XmlNameTable utilizado para comparaciones de cadenas atomizadas en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable method


Devuelve el [XmlNameTable](../../xmlnametable/) utilizado para comparaciones de cadenas atomizadas.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### ReturnValue

El [XmlNameTable](../../xmlnametable/) que almacena todas las cadenas atomizadas utilizadas por todas las instancias de [XmlReader](../../xmlreader/) creadas con este objeto [XmlReaderSettings](../). El valor predeterminado es **nullptr**. La instancia de [XmlReader](../../xmlreader/) creada utilizará una nueva [NameTable](../../nametable/) vacía si este valor es **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
