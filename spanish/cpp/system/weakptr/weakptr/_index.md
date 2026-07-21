---
title: "System::WeakPtr::WeakPtr constructor"
linktitle: "WeakPtr"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::WeakPtr::WeakPtr constructor. Crea un puntero débil que referencia el mismo puntero al que apunta x en C++."
type: docs
weight: 100
url: /es/cpp/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor


Crea un puntero débil que referencia el mismo puntero al que apunta x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


| Parámetro | Descripción |
| --- | --- |
| Q | Tipo apuntado del puntero fuente. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Puntero desde el cual copiar el valor del apuntado. |

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const SmartPtr_\&) constructor


Crea un puntero débil que referencia el mismo puntero al que apunta ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Puntero desde el cual copiar el valor del apuntado. |

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor


Construye por copia el puntero débil.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const WeakPtr\<Q\>\& | Puntero desde el cual copiar el valor del apuntado. |

## Ver también

* Class [WeakPtr](../)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr_\&) constructor


Construye por copia el puntero débil.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const WeakPtr_\& | Puntero desde el cual copiar el valor del apuntado. |

## Ver también

* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(Pointee_ *) constructor


Crea un puntero débil al objeto dado.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | Pointee_ * | [Object](../../object/) para crear un puntero débil a. |

## Ver también

* Typedef [Pointee_](../pointee_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(SmartPtr_\&&) constructor


Construye por movimiento el puntero débil.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | SmartPtr_\&& | Puntero del que mover el valor apuntado. |

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(std::nullptr_t) constructor


Crea un puntero nulo.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## Ver también

* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
