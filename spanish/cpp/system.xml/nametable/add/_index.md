---
title: "Método System::Xml::NameTable::Add"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::NameTable::Add método. Atomiza la cadena especificada y la agrega a la NameTable en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/nametable/add/
---
## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Atomiza la cadena especificada y la agrega a la [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const ArrayPtr\<char16_t\>\& | La matriz de caracteres que contiene la cadena a agregar. |
| inicio | int32_t | El índice basado en cero en la matriz que especifica el primer carácter de la cadena. |
| len | int32_t | El número de caracteres en la cadena. |

### ReturnValue

La cadena atomizada o la cadena existente si ya existe en la [NameTable](../). Si **len** es cero, se devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## NameTable::Add(const String\&) method


Atomiza la cadena especificada y la agrega a la [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const String\& | La cadena a agregar. |

### ReturnValue

La cadena atomizada o la cadena existente si ya existe en la [NameTable](../).

## Ver también

* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
