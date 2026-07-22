---
title: "System::WeakReference< T >‑klass"
linktitle: "WeakReference< T >"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::WeakReference< T >‑klass. Representerar en svag referens, som refererar till ett objekt samtidigt som objektet fortfarande kan tas bort i C++."
type: docs
weight: 8000
url: /sv/cpp/system/weakreference_t_/
---
## WeakReference< T > class


Representerar en svag referens som refererar ett objekt samtidigt som objektet fortfarande kan tas bort.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av ett refererat objekt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [operator!=](./operator!=/)(std::nullptr_t) const | Kontrollerar om det refererade objektet inte är null. |
| [operator!=](./operator!=/)(const WeakReference\<T\>\&) const | Jämför det refererade objektet med en annan instans av klassen [WeakReference](../weakreference/). |
| [operator==](./operator==/)(std::nullptr_t) const | Kontrollerar om det refererade objektet är null. |
| [operator==](./operator==/)(const WeakReference\<T\>\&) const | Jämför det refererade objektet med en annan instans av klassen [WeakReference](../weakreference/). |
| [reset](./reset/)() |  |
| [SetTarget](./settarget/)(const SmartPtr\<T\>\&) | Ställer in objektet (målet) som refereras av det aktuella [WeakReference](../weakreference/) objektet. |
| [TryGetTarget](./trygettarget/)(const SmartPtr\<T\>\&) const | Hämtar objektet (målet) som refereras av det aktuella [WeakReference](../weakreference/) objektet. |
| [WeakReference](./weakreference/)() | Standardkonstruktor. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor från nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&) | Initierar en ny instans av [WeakReference](../weakreference/) klassen, som refererar till det angivna objektet. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&, bool) | Initierar en ny instans av [WeakReference](../weakreference/) klassen, som refererar till det angivna objektet. |

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
