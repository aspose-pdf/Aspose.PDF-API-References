---
title: "System::MakeObject‑metod"
linktitle: "MakeObject"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MakeObject‑metod. Skapar ett objekt på heapen och returnerar en delad pekare till det i C++."
type: docs
weight: 25300
url: /sv/cpp/system/makeobject/
---
## System::MakeObject(Args\&&...) method


Skapar ett objekt på heapen och returnerar en delad pekare till det.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Klass att instansiera. |
| Argument | Konstruktörsargumentens typer. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Konstruktörsargument. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeObject(Args\&&...) method


Skapar ett objekt på heapen och returnerar en delad pekare till det.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [SmartPtr](../smartptr/) till klass att instansiera. |
| Argument | Konstruktörsargumentens typer. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Konstruktörsargument. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
