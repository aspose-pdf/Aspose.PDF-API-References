---
title: "System::SmartPtr::operator= método"
linktitle: "operator="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::SmartPtr::operator= método. Asigna por copia el objeto SmartPtr. Realiza las conversiones de tipo requeridas en C++."
type: docs
weight: 2800
url: /es/cpp/system/smartptr/operator=/
---
## SmartPtr::operator=(const SmartPtr\<Q\>\&) method


Asigna por copia el objeto [SmartPtr](../). Realiza las conversiones de tipo requeridas.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado por x. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Puntero para asignación por copia. |

### ReturnValue

Referencia a este objeto.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(const SmartPtr_\&) method


Copia-asigna el objeto [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const SmartPtr_\& | Puntero para asignación por copia. |

### ReturnValue

Referencia a este objeto.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(Pointee_ *) method


Asigna un puntero crudo al objeto [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | Pointee_ * | Valor del puntero a asignar. |

### ReturnValue

Referencia a este objeto.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(SmartPtr_\&&) method


Mueve-asigna el objeto [SmartPtr](../). x se vuelve inutilizable.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | SmartPtr_\&& | Puntero a mover-asignar. |

### ReturnValue

Referencia a este objeto.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(std::nullptr_t) method


Establece el valor del puntero a nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### ReturnValue

Referencia a este objeto.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
