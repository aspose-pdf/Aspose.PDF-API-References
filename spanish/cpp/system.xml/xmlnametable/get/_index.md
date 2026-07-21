---
title: "System::Xml::XmlNameTable::Get método"
linktitle: "Obtener"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNameTable::Get método. Cuando se sobrescribe en una clase derivada, obtiene la cadena atomizada que contiene los mismos caracteres que el rango especificado de caracteres en la matriz dada en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Cuando se sobrescribe en una clase derivada, obtiene la cadena atomizada que contiene los mismos caracteres que el rango de caracteres especificado en la matriz dada.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const ArrayPtr\<char16_t\>\& | La matriz de caracteres que contiene el nombre a buscar. |
| desplazamiento | int32_t | El índice basado en cero en la matriz que especifica el primer carácter del nombre. |
| longitud | int32_t | El número de caracteres en el nombre. |

### ReturnValue

La cadena atomizada o **nullptr** si la cadena no ha sido atomizada previamente. Si **length** es cero, se devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Get(const String\&) method


Cuando se sobrescribe en una clase derivada, obtiene la cadena atomizada que contiene el mismo valor que la cadena especificada.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const String\& | El nombre a buscar. |

### ReturnValue

La cadena atomizada o **nullptr** si la cadena no ha sido atomizada previamente.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
