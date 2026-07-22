---
title: "System::DynamicWeakPtr::Reference klass"
linktitle: "Reference"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DynamicWeakPtr::Reference klass. Referensklass som säkerställer att DynamicWeakPtr::Apply anropas. Används om DynamicWeakPtr skickas som SmartPtr-referensparameter till en funktion som kan tilldela den i C++."
type: docs
weight: 700
url: /sv/cpp/system/dynamicweakptr/reference/
---
## Reference class


[Reference](./) class which ensures that DynamicWeakPtr::Apply is called. Used if [DynamicWeakPtr](../) is passed as [SmartPtr](../../smartptr/) reference parameter to function which may assign to it.

```cpp
class Reference
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [operator DynamicWeakPtr_ &](./operatordynamicweakptr_&/)() const | Konverteringsoperator. Tillåter att använda [Reference](./) i sammanhang där [DynamicWeakPtr_](../dynamicweakptr_/) behövs. |
| [Reference](./reference/)(DynamicWeakPtr_\&) | Skapar smart pekarreferens. |
| [Reference](./reference/)(Reference\&&) | Flyttkonstruktor för smart pekarreferens. |
| [~Reference](./~reference/)() | Förstör referens. Säkerställer att Apply() anropas på den refererade smarta pekaren. |
## Se även

* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
