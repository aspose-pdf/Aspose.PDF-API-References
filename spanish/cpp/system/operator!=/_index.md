---
title: "Método System::operator!=."
linktitle: "operator!="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método operator!= de la clase en C++."
type: docs
weight: 26600
url: /es/cpp/system/operator!=/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) method




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## Ver también

* Class [ArraySegment](../arraysegment/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(Chars\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


| Parámetro | Descripción |
| --- | --- |
| Chars | Tipo literal [String](../string/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | Chars\& | Literal [String](../string/) para comparar. |
| right | const String\& | [String](../string/) para comparar. |

### ReturnValue

false si las cadenas coinciden, true en caso contrario.

## Ver también

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SharedPtr\<Object\>\&, const String\&) method


[Object](../object/) and string comparison.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const SharedPtr\<Object\>\& | [Object](../object/) para convertir a cadena y comparar. |
| right | const String\& | [String](../string/) para comparar. |

### ReturnValue

false si la representación en cadena del objeto es igual a la cadena, true en caso contrario.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) method


Determina si los URIs representados por los objetos actual y especificado no son iguales.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | El primer objeto [Uri](../uri/) a comparar |
| uri2 | const SharedPtr\<Uri\>\& | El segundo objeto [Uri](../uri/) a comparar |

### ReturnValue

Verdadero si los URIs no son iguales, de lo contrario - falso

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Uri](../uri/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) method


Compara dos punteros inteligentes para determinar si no son iguales.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado del primer puntero. |
| Y | Tipo del objeto apuntado del segundo puntero. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | Primer puntero a comparar. |
| y | const SmartPtr\<Y\>\& | Segundo puntero a comparar. |

### ReturnValue

Falso si los punteros coinciden, verdadero de lo contrario.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const Y *) method


Comparación de desigualdad entre un puntero inteligente y un puntero simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


| Parámetro | Descripción |
| --- | --- |
| X | tipo del puntero inteligente. |
| Y | tipo del puntero simple. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | puntero inteligente a comparar (izquierda). |
| y | const Y * | puntero a comparar (derecha). |

### ReturnValue

Falso si los punteros coinciden, verdadero de lo contrario.

## Ver también

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const T1\&, const Nullable\<T2\>\&) method


Determina si el valor especificado no es igual al valor representado por el objeto [Nullable](../nullable/) especificado al aplicar [operator!=()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del primer valor comparado |
| T2 | El tipo subyacente del objeto [Nullable](../nullable/) que representa el segundo valor comparado |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alguno | const T1\& | Una referencia constante al valor que se usará como el primer operando |
| other | const Nullable\<T2\>\& | Una referencia constante al objeto [Nullable](../nullable/) cuyo valor representado se usará como el segundo comparando |

### ReturnValue

Verdadero si los comparandos no son iguales, de lo contrario - falso

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const X *, const SmartPtr\<Y\>\&) method


Comparación de igualdad del puntero inteligente contra un puntero simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


| Parámetro | Descripción |
| --- | --- |
| X | tipo del puntero simple. |
| Y | tipo del puntero inteligente. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const X * | puntero a comparar (derecha). |
| y | const SmartPtr\<Y\>\& | puntero inteligente a comparar (izquierda). |

### ReturnValue

Falso si los punteros coinciden, verdadero de lo contrario.

## Ver también

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) method


Comprueba si el puntero inteligente no es nulo.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado por el puntero. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | SmartPtr\<X\> const\& | Puntero a comprobar. |

### ReturnValue

Falso si el puntero es nulo, verdadero de lo contrario.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## Ver también

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) method


Determina si el objeto [Nullable](../nullable/) especificado representa un valor que no es igual a nulo.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | std::nullptr_t | Una referencia constante a un objeto [Nullable](../nullable/) para probar |

### ReturnValue

Verdadero si el objeto especificado representa un valor no nulo, falso de lo contrario

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const String\&) method


Comprueba si la cadena es nula.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) a comprobar. |

### ReturnValue

falso si la cadena es nula, verdadero de lo contrario.

## Ver también

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, DateTime) method




```cpp
bool System::operator!=(std::nullptr_t, DateTime)
```

## Ver también

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) method


Comprueba si el puntero inteligente no es nulo.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado por el puntero. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | std::nullptr_t | Puntero a comprobar. |

### ReturnValue

Falso si el puntero es nulo, verdadero de lo contrario.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator!=(std::nullptr_t, TimeSpan)
```

## Ver también

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(T\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero [String](../string/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | T\& | Puntero [String](../string/) para comparar. |
| right | const String\& | [String](../string/) para comparar. |

### ReturnValue

false si las cadenas coinciden, true en caso contrario.

## Ver también

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
