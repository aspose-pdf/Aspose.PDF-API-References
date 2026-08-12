---
title: "Método System::Xml::XmlNameTable::Add"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlNameTable::Add. Cuando se sobrescribe en una clase derivada, atomiza la cadena especificada y la agrega a XmlNameTable en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Cuando se sobrescribe en una clase derivada, atomiza la cadena especificada y la agrega a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const ArrayPtr\<char16_t\>\& | La matriz de caracteres que contiene el nombre a agregar. |
| desplazamiento | int32_t | Índice basado en cero en la matriz que especifica el primer carácter del nombre. |
| longitud | int32_t | El número de caracteres en el nombre. |

### ReturnValue

La nueva cadena atomizada o la existente si ya existe. Si length es cero, se devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Add(const String\&) method


Cuando se sobrescribe en una clase derivada, atomiza la cadena especificada y la agrega a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const String\& | El nombre a agregar. |

### ReturnValue

La nueva cadena atomizada o la existente si ya existe.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
