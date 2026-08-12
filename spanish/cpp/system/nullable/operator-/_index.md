---
title: "Método System::Nullable::operator-"
linktitle: "operador-"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::operator-. Resta valores nullable en C++."
type: docs
weight: 1400
url: /es/cpp/system/nullable/operator-/
---
## Nullable::operator-(const Nullable\<T1\>\&) const method


Resta valores anulables.

```cpp
template<typename T1> System::Nullable<decltype(get_Value() - other.get_Value())> System::Nullable<T>::operator-(const Nullable<T1> &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const Nullable\<T1\>\& | valor a restar. |

### ReturnValue

Resultado de la resta.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-(const T1\&) const method


Resta valores anulables y no anulables.

```cpp
template<typename T1,typename> Nullable<decltype(get_Value() - other)> System::Nullable<T>::operator-(const T1 &other) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | valor a restar. |

### ReturnValue

Resultado de la resta.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-(T1) const method


Resta valores anulables y apuntados a nulo.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho, debe ser nullptr_t. |

### ReturnValue

Objeto [Nullable](../) vacío.

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
