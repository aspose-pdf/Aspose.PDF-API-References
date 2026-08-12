---
title: "System::WeakPtr::WeakPtr‑konstruktor"
linktitle: "WeakPtr"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::WeakPtr::WeakPtr‑konstruktor. Skapar en svag pekare som refererar till samma pekare som x pekar på i C++."
type: docs
weight: 100
url: /sv/cpp/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor


Skapar svag pekare som refererar till samma pekare som x pekar på.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


| Parameter | Beskrivning |
| --- | --- |
| Q | Pekartyp för källpekare. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pekare att kopiera pekarens värde från. |

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const SmartPtr_\&) constructor


Skapar svag pekare som refererar till samma pekare som ptr pekar på.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Pekare att kopiera pekarens värde från. |

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor


Kopierar och konstruerar svag pekare.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


| Parameter | Beskrivning |
| --- | --- |
| Q | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const WeakPtr\<Q\>\& | Pekare att kopiera pekarens värde från. |

## Se även

* Class [WeakPtr](../)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr_\&) constructor


Kopierar och konstruerar svag pekare.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const WeakPtr_\& | Pekare att kopiera pekarens värde från. |

## Se även

* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(Pointee_ *) constructor


Skapar svag pekare till angivet objekt.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | Pointee_ * | [Object](../../object/) för att skapa svag pekare till. |

## Se även

* Typedef [Pointee_](../pointee_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(SmartPtr_\&&) constructor


Flyttar och konstruerar svag pekare.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | SmartPtr_\&& | Pekare att flytta pekarens värde från. |

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(std::nullptr_t) constructor


Skapar nullpekare.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## Se även

* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
