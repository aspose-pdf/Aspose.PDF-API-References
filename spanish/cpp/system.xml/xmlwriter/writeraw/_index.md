---
title: "Método System::Xml::XmlWriter::WriteRaw"
linktitle: "WriteRaw"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlWriter::WriteRaw. Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde un búfer de caracteres en C++."
type: docs
weight: 2900
url: /es/cpp/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method


Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde un búfer de caracteres.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<char16_t\> | Arreglo de caracteres que contiene el texto a escribir. |
| índice | int32_t | La posición dentro del búfer que indica el inicio del texto a escribir. |
| count | int32_t | El número de caracteres a escribir. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteRaw(const String\&) method


Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde una cadena.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const String\& | [String](../../../system/string/) que contiene el texto a escribir. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
