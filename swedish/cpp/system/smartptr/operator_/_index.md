---
title: "System::SmartPtr::operator* method"
linktitle: "operator*"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtr::operator* method. Hämtar referens till pekat objekt. Assertar att pekaren inte är null i C++."
type: docs
weight: 2500
url: /sv/cpp/system/smartptr/operator_/
---
## SmartPtr::operator* method


Hämtar referens till det pekade objektet. Påstår att pekaren inte är null.

```cpp
Pointee_ & System::SmartPtr<T>::operator*() const
```


### ReturnValue

Referens till pekat objekt.

## Se även

* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
titel: System::SmartPtr::operator< method
linktitle: operator<
second_title: Aspose.PDF för C++ API-referens
beskrivning: 'System::SmartPtr::operator< method. Tillhandahåller mindre-jämförelse semantik för SmartPtr-klassen i C++.'
type: dokument
vikt: 2700
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Tillhandahåller mindre-jämförelse semantik för [SmartPtr](../) klass.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Typ av pekare att jämföra den aktuella med. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | SmartPtr\<Y\> const\& | Pekare att jämföra den aktuella med. |

### ReturnValue

Sant om objektet som refereras av [SmartPtr](../) är 'mindre' än x och falskt annars.

## Se även

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator<(Y *) const method


Tillhandahåller mindre-jämförelse semantik för [SmartPtr](../) klass.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Typ av pekare att jämföra den aktuella med. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | Y * | Pekare att jämföra den aktuella med. |

### ReturnValue

Sant om objektet som refereras av [SmartPtr](../) är 'mindre' än p och falskt annars.

## Se även

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
