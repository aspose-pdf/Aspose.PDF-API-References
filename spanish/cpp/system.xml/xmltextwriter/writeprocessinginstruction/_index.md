---
title: "System::Xml::XmlTextWriter::WriteProcessingInstruction método"
linktitle: "WriteProcessingInstruction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextWriter::WriteProcessingInstruction método. Escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente forma: <?name text?> en C++."
type: docs
weight: 3300
url: /es/cpp/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction method


Escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente manera: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la instrucción de procesamiento. |
| text | String | [Text](../../../system.text/) para incluir en la instrucción de procesamiento. |
## Observaciones



Este método se está utilizando para crear una declaración XML después de que se haya llamado a [XmlTextWriter::WriteStartDocument](../writestartdocument/).
## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
