---
title: "System::Xml::XmlDocument::ReadNode método"
linktitle: "ReadNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlDocument::ReadNode. Crea un objeto XmlNode basado en la información del XmlReader. El lector debe estar posicionado en un nodo o atributo en C++."
type: docs
weight: 3600
url: /es/cpp/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode method


Crea un objeto [XmlNode](../../xmlnode/) basado en la información del [XmlReader](../../xmlreader/). El lector debe estar posicionado en un nodo o atributo.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lector | SharedPtr\<XmlReader\> | El origen XML. |

### ReturnValue

El nuevo [XmlNode](../../xmlnode/) o **nullptr** si no existen más nodos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
