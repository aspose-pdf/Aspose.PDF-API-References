---
title: "System::WeakPtr-klass"
linktitle: "WeakPtr"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::WeakPtr-klass. Subklass till System::SmartPtr som sätter sig i svagt läge vid konstruktion. Observera att denna klass inte garanterar att dess instans alltid förblir i svagt läge eftersom set_Mode() fortfarande är åtkomlig. Denna typ är en pekare för att hantera raderingen av andra objekts. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens i C++."
type: docs
weight: 7800
url: /sv/cpp/system/weakptr/
---
## WeakPtr class


Subklass till [System::SmartPtr](../smartptr/) som sätter sig i svagt läge vid konstruktion. Observera att denna klass inte garanterar att dess instans alltid förblir i svagt läge eftersom [set_Mode()](../smartptr/set_mode/) fortfarande är åtkomlig. Denna typ är en pekare för att hantera raderingen av andra objekts. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Pekartyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [expired](./expired/)() const | Kontrollerar om det refererade objektet redan har raderats. |
| [get_weak](./get_weak/)() const | Hämtar det refererade objektet. Påstår att pekaren är i svagt läge. |
| [operator=](./operator=/)(Q\&&) | Tilldelar värde till svag pekare. Anropar den specifika tilldelningsoperatorn för [SmartPtr_](./smartptr_/). |
| [operator==](./operator==/)(std::nullptr_t) const | Kontrollerar om svag pekare är null. |
| [WeakPtr](./weakptr/)(std::nullptr_t) | Skapar nullpekare. |
| [WeakPtr](./weakptr/)(Pointee_ *) | Skapar svag pekare till angivet objekt. |
| [WeakPtr](./weakptr/)(const SmartPtr_\&) | Skapar svag pekare som refererar till samma pekare som ptr pekar på. |
| [WeakPtr](./weakptr/)(const SmartPtr\<Q\>\&) | Skapar svag pekare som refererar till samma pekare som x pekar på. |
| [WeakPtr](./weakptr/)(const WeakPtr_\&) | Kopierar och konstruerar svag pekare. |
| [WeakPtr](./weakptr/)(const WeakPtr\<Q\>\&) | Kopierar och konstruerar svag pekare. |
| [WeakPtr](./weakptr/)(SmartPtr_\&&) | Flyttar och konstruerar svag pekare. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Pointee_](./pointee_/) | Pekad typ. |
| [SmartPtr_](./smartptr_/) | Alias för motsvarande [SmartPtr](../smartptr/) klass. |
| [WeakPtr_](./weakptr_/) | Alias för egen typ. |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
