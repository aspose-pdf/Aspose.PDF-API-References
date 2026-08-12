---
title: "System::MakeSharedPtr method"
linktitle: "MakeSharedPtr"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MakeSharedPtr method. Konverterar rå pekare till smart pekare. Överlagring för const-pekare. Användbart t.ex. när man använder ''this''-variabeln i C#-metoder som översätts som const i C++."
type: docs
weight: 25600
url: /sv/cpp/system/makesharedptr/
---
## System::MakeSharedPtr(const X *) method


Konverterar rå pekare till smart pekare. Överlagring för const-pekare. Användbart t.ex. när man använder 'this'-variabeln i C#-metoder som översätts som const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


| Parameter | Beskrivning |
| --- | --- |
| X | Pekartyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | const X * | Rå pekare till objekt. |

### ReturnValue

Delad smart pekare till objekt.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeSharedPtr(X *) method


Konverterar rå pekare till smart pekare.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


| Parameter | Beskrivning |
| --- | --- |
| X | Pekartyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | X * | Rå pekare till objekt. |

### ReturnValue

Delad smart pekare till objekt.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
