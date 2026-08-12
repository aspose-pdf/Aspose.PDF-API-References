---
title: "Método System::Object::Equals"
linktitle: "Igual"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Object::Equals. Compara objetos usando la semántica de C# Object.Equals en C++."
type: docs
weight: 300
url: /es/cpp/system/object/equals/
---
## Object::Equals(ptr) method


Compara objetos usando la semántica de C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | ptr | [Object](../) para comparar con el actual. |

### ReturnValue

Verdadero si los objetos se consideran iguales y falso en caso contrario.

## Ver también

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(double const\&, double const\&) method


Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | double const\& | Valor de punto flotante del LHS. |
| objB | double const\& | Valor de punto flotante del RHS. |

### ReturnValue

Verdadero si **objA** y **objB** son ambos NaN o iguales, falso en caso contrario.

## Ver también

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(float const\&, float const\&) method


Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | float const\& | Valor de punto flotante del LHS. |
| objB | float const\& | Valor de punto flotante del RHS. |

### ReturnValue

Verdadero si **objA** y **objB** son ambos NaN o iguales, falso en caso contrario.

## Ver también

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Compara objetos de tipo referencia al estilo de C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del primer objeto a comparar. |
| T2 | Tipo del segundo objeto a comparar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T1 const\& | Primer objeto a comparar. |
| objB | T2 const\& | Segundo objeto a comparar. |

### ReturnValue

Verdadero si los objetos coinciden ya sea por referencia o semánticamente (por una comparación similar a [Object.Equals](./)), falso en caso contrario.

## Ver también

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Compara objetos de tipo valor al estilo de C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del primer objeto a comparar. |
| T2 | Tipo del segundo objeto a comparar. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T1 const\& | Primer objeto a comparar. |
| objB | T2 const\& | Segundo objeto a comparar. |

### ReturnValue

Verdadero si los objetos se consideran iguales mediante el operador de igualdad disponible, falso en caso contrario.

## Ver también

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
