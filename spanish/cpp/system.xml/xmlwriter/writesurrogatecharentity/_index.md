---
title: "Método System::Xml::XmlWriter::WriteSurrogateCharEntity"
linktitle: "WriteSurrogateCharEntity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlWriter::WriteSurrogateCharEntity. Cuando se sobrescribe en una clase derivada, genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos en C++."
type: docs
weight: 3400
url: /es/cpp/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity method


Cuando se sobrescribe en una clase derivada, genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowChar | char16_t | El sustituto bajo. Debe ser un valor entre 0xDC00 y 0xDFFF. |
| highChar | char16_t | El sustituto alto. Debe ser un valor entre 0xD800 y 0xDBFF. |

## Ver también

* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
