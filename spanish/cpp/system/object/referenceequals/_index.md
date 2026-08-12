---
title: "Método System::Object::ReferenceEquals."
linktitle: "ReferenceEquals"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Object::ReferenceEquals. Especialización de Object::ReferenceEquals para el caso de cadena y nullptr en C++."
type: docs
weight: 1200
url: /es/cpp/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method


Especialización de [Object::ReferenceEquals](./) para el caso de cadena y nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String const\& | [String](../../string/) para comparar con nullptr. |

### ReturnValue

true si la cadena es null, false en caso contrario.

## Ver también

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(String const\&, String const\&) method


Especialización de [Object::ReferenceEquals](./) para el caso de cadenas.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str1 | String const\& | Primera cadena para comparar. |
| str2 | String const\& | Segunda cadena para comparar. |

### ReturnValue

true si las cadenas coinciden, false en caso contrario.

## Ver también

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(ptr const\&, ptr const\&) method


Compara objetos por referencia.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | ptr const\& | Primer puntero a comparar. |
| objB | ptr const\& | Segundo puntero a comparar. |

### ReturnValue

Verdadero si los punteros coinciden y falso en caso contrario.

## Ver también

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Compara por referencia un objeto de tipo valor con nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a comparar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T const\& | Primer objeto a comparar. |

### ReturnValue

Siempre devuelve falso ya que los tipos de valor no pueden ser anulados.

## Ver también

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, T const\&) method


Compara objetos por referencia.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objetos a comparar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T const\& | Primer objeto a comparar. |
| objB | T const\& | Segundo objeto a comparar. |

### ReturnValue

Verdadero si las direcciones de los objetos coinciden y falso en caso contrario.

## Ver también

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
