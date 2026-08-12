---
title: "System::SmartPtr::operator= method"
linktitle: "operator="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtr::operator= method. Kopierar‑tilldelar SmartPtr‑objekt. Utför nödvändiga typkonverteringar i C++."
type: docs
weight: 2800
url: /sv/cpp/system/smartptr/operator=/
---
## SmartPtr::operator=(const SmartPtr\<Q\>\&) method


Kopierar‑tilldelar [SmartPtr](../)‑objekt. Utför nödvändiga typkonverteringar.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


| Parameter | Beskrivning |
| --- | --- |
| Q | Typ av objekt som pekas på av x. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pekare till kopierings‑tilldelning. |

### ReturnValue

Referens till detta objekt.

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(const SmartPtr_\&) method


Kopierar‑tilldelar [SmartPtr](../)‑objekt.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const SmartPtr_\& | Pekare till kopierings‑tilldelning. |

### ReturnValue

Referens till detta objekt.

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(Pointee_ *) method


Tilldelar rå pekare till [SmartPtr](../)‑objekt.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | Pointee_ * | Pekarvärde att tilldela. |

### ReturnValue

Referens till detta objekt.

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(SmartPtr_\&&) method


Flytt‑tilldelar [SmartPtr](../)‑objekt. x blir oanvändbar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | SmartPtr_\&& | Pekare till flytt‑tilldelning. |

### ReturnValue

Referens till detta objekt.

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(std::nullptr_t) method


Sätter pekarvärde till nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### ReturnValue

Referens till detta objekt.

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
