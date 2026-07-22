---
title: "System::WeakReference<> klass"
linktitle: "WeakReference<>"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::WeakReference<> klass. Representerar en svag referens, som refererar till ett objekt samtidigt som objektet fortfarande kan tas bort i C++."
type: docs
weight: 8100
url: /sv/cpp/system/weakreference__/
---
## WeakReference<> class


Representerar en svag referens som refererar ett objekt samtidigt som objektet fortfarande kan tas bort.

```cpp
class WeakReference<> : public System::WeakReference<System::Object>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsAlive](./get_isalive/)() const | Hämtar en indikation på om objektet som refereras av det aktuella [WeakReference](../weakreference/) objektet har tagits bort. |
| [get_Target](./get_target/)() const | Hämtar objektet (målet) som refereras av det aktuella [WeakReference](../weakreference/) objektet. |
| [set_Target](./set_target/)(const SmartPtr\<Object\>\&) | Ställer in objektet (målet) som refereras av det aktuella [WeakReference](../weakreference/) objektet. |
| [WeakReference](./weakreference/)() | Standardkonstruktor. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor från nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&) | Initierar en ny instans av [WeakReference](../weakreference/) klassen, som refererar till det angivna objektet. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&, bool) | Initierar en ny instans av [WeakReference](../weakreference/) klassen, som refererar till det angivna objektet. |
## Se även

* Class [WeakReference](../weakreference/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
