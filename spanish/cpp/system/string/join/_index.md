---
title: "Método System::String::Join"
linktitle: "Join"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::String::Join. Une un arreglo usando la cadena como separador en C++."
type: docs
weight: 7300
url: /es/cpp/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method


Une el arreglo usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const String\& | [String](../) para colocar entre los elementos del arreglo al unirlos. |
| parts | const ArrayPtr\<SharedPtr\<Object\>\>\& | [Array](../../array/) de partes a unir. |

### ReturnValue

[String](../) representing joint elements.

## Ver también

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method


Une el arreglo usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const String\& | [String](../) para colocar entre los elementos del arreglo al unirlos. |
| parts | const ArrayPtr\<String\>\& | [Array](../../array/) de partes a unir. |
| startIndex | int | Primer índice en el arreglo desde donde comenzar a unir. |
| count | int | Número de elementos del arreglo a unir. -1 significa 'hasta que el arreglo termine'. |

### ReturnValue

[String](../) representing joint array elements.

## Ver también

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method


Une el arreglo usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const String\& | [String](../) para colocar entre los elementos del arreglo al unirlos. |
| partes | const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\& | - objeto enumerable de partes |

### ReturnValue

[String](../) representing joint elements.

## Ver también

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method


Une el arreglo usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const String\& | [String](../) para colocar entre los elementos del arreglo al unirlos. |
| partes | const System::Details::ArrayView\<String\>\& | ArrayView de partes a unir. |
| startIndex | int | Primer índice en el arreglo desde donde comenzar a unir. |
| count | int | Número de elementos del arreglo a unir. -1 significa 'hasta que el arreglo termine'. |

### ReturnValue

[String](../) representing joint array elements.

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
