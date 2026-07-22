---
title: "System::DynamicWeakPtr‑klass"
linktitle: "DynamicWeakPtr"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DynamicWeakPtr‑klass. Smartpekarklass som spårar pekarlägen för mallargumenten i det lagrade objektet och uppdaterar dem efter varje tilldelning. Denna typ är en pekare för att hantera en annan objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens i C++."
type: docs
weight: 2300
url: /sv/cpp/system/dynamicweakptr/
---
## DynamicWeakPtr class


Smartpekarklass som spårar pekarlägen för mallargumenten i det lagrade objektet och uppdaterar dem efter varje tilldelning. Denna typ är en pekare för att hantera raderingen av ett annat objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


| Parameter | Beskrivning |
| --- | --- |
| Pointee | typ. |
| trunkMode | Läge för smartpekaren själv, delad eller svag. |
| weakLeafs | Index för mallargumenten av den lagrade typen som bör sättas till svagt pekarläge. |
## Nested classes

* Class [Reference](./reference/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Skapar en null smartpekare. |
| [DynamicWeakPtr](./dynamicweakptr/)(Pointee_ *) | Skapar en smartpekare som pekar på det givna objektet. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr_\&) | Kopieringskonstruktor för smartpekare. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr\<Q\>\&) | Kopieringskonstruktor för smartpekare. |
| [DynamicWeakPtr](./dynamicweakptr/)(const DynamicWeakPtr_\&) | Kopieringskonstruktor för smartpekare. |
| [DynamicWeakPtr](./dynamicweakptr/)(SmartPtr_\&&) | Flyttkonstruktor för smartpekare. |
| [operator=](./operator=/)(SmartPtr_\&&) | Flytttilldelning av smartpekare. |
| [operator=](./operator=/)(const SmartPtr_\&) | Kopieringstilldelning av smartpekare. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Kopieringstilldelning av smartpekare. |
| [operator=](./operator=/)(typename SmartPtr_::Pointee_ *) | Tilldelar smart pekare. |
| [operator=](./operator=/)(std::nullptr_t) | Sätter smart pekare till null. |
| [operator==](./operator==/)(std::nullptr_t) const | Kontrollerar om smart pekare är null. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Självtyp alias. |
| [Pointee_](./pointee_/) | Pekad typ. |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) basisklass alias. |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
