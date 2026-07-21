---
title: "Método System::Xml::XmlWriter::WriteProcessingInstruction"
linktitle: "WriteProcessingInstruction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlWriter::WriteProcessingInstruction método. Cuando se sobrescribe en una clase derivada, escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente forma: <?name text?> en C++."
type: docs
weight: 2700
url: /es/cpp/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction method


Cuando se sobrescribe en una clase derivada, escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente manera: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre de la instrucción de procesamiento. |
| text | String | El texto a incluir en la instrucción de procesamiento. |
## Observaciones



Este método se está utilizando para crear una declaración XML después de que se haya llamado a [XmlWriter::WriteStartDocument](../writestartdocument/).
## Ver también

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
