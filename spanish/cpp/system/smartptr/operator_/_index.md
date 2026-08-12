---
title: "Método System::SmartPtr::operator*"
linktitle: "operador*"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::SmartPtr::operator*. Obtiene una referencia al objeto apuntado. Asegura que el puntero no sea nulo en C++."
type: docs
weight: 2500
url: /es/cpp/system/smartptr/operator_/
---
## SmartPtr::operator* method


Obtiene una referencia al objeto apuntado. Asegura que el puntero no sea nulo.

```cpp
Pointee_ & System::SmartPtr<T>::operator*() const
```


### ReturnValue

Referencia al objeto apuntado.

## Ver también

* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
título: System::SmartPtr::operator< method
linktitle: operator<
second_title: Referencia de API de Aspose.PDF para C++
descripción: 'System::SmartPtr::operator< method. Proporciona semántica de comparación menor para la clase SmartPtr en C++.'
type: docs
peso: 2700
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Proporciona semántica de comparación menor para la clase [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo de puntero con el que comparar el actual. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | SmartPtr\<Y\> const\& | Puntero con el que comparar el actual. |

### ReturnValue

Verdadero si el objeto referenciado por [SmartPtr](../) es 'menor' que x y falso en caso contrario.

## Ver también

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator<(Y *) const method


Proporciona semántica de comparación menor para la clase [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo de puntero con el que comparar el actual. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | Y * | Puntero con el que comparar el actual. |

### ReturnValue

Verdadero si el objeto referenciado por [SmartPtr](../) es 'menor' que p y falso en caso contrario.

## Ver también

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
