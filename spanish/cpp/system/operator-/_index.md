---
title: "método System::operator-"
linktitle: "operador-"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "método System::operator-. Devuelve una nueva instancia de la clase Decimal que representa un valor que es el resultado de la resta del valor representado por el objeto Decimal especificado del valor especificado en C++."
type: docs
weight: 28900
url: /es/cpp/system/operator-/
---
## System::operator-(const T\&, const Decimal\&) method


Devuelve una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es el resultado de la resta del valor representado por el objeto [Decimal](../decimal/) especificado del valor especificado.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const T\& | El valor del cual restar |
| d | const Decimal\& | El objeto [Decimal](../decimal/) que representa el valor restado |

### ReturnValue

Una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es el resultado de la resta del valor representado por **d** de **x**.

## Ver también

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(const T1\&, const Nullable\<T2\>\&) method


Resta valores no anulables y anulables.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some - other.get_Value())> System::operator-(const T1 &some, const Nullable<T2> &other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando izquierdo. |
| T2 | Tipo del operando derecho. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alguno | const T1\& | Operando izquierdo. |
| otro | const Nullable\<T2\>\& | Operando derecho. |

### ReturnValue

Resultado de la subestación.

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(DayOfWeek, DayOfWeek) method


Calcula el número de días entre dos días de la semana.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | DayOfWeek | El minuendo |
| b | DayOfWeek | El sustraendo |

### ReturnValue

El número de días entre los días laborables **a** y **b**; el valor de retorno es un número negativo si *ocurre* después de ****

## Ver también

* Enum [DayOfWeek](../dayofweek/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Desconecta todas las callbacks en el delegado de la mano derecha desde el final de la lista de callbacks del delegado de la mano izquierda.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | El delegado del cual se eliminarán las callbacks. |
| rhv | MulticastDelegate\<T\> | El delegado cuyas callbacks serán eliminadas. |

### ReturnValue

Devuelve un delegado que contiene las callbacks del valor de la mano izquierda, pero sin las del valor de la mano derecha.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
