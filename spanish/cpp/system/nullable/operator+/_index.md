---
title: "Método System::Nullable::operator+"
linktitle: "operador+"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::operator+. Suma valores nullable en C++."
type: docs
weight: 1200
url: /es/cpp/system/nullable/operator+/
---
## Nullable::operator+(const Nullable\<T1\>\&) const method


Suma valores anulables.

```cpp
template<typename T1> System::Nullable<decltype(get_Value()+other.get_Value())> System::Nullable<T>::operator+(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const Nullable\<T1\>\& | valor a añadir. |

### ReturnValue

Resultado de la suma.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+(const T1\&) const method


Suma valores anulables y no anulables.

```cpp
template<typename T1,typename> Nullable<decltype(get_Value()+other)> System::Nullable<T>::operator+(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | valor a añadir. |

### ReturnValue

Resultado de la suma.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+(std::nullptr_t) const method


Devuelve una instancia construida por defecto de la clase Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
