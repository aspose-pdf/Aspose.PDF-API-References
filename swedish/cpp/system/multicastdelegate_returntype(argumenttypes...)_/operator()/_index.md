---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() metod"
linktitle: "operator()"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() metod. Anropar alla delegater som för närvarande finns i delegatsamlingen. Delegater anropas i samma ordning som de lades till i samlingen. Operatören blockerar medan delegaterna körs i C++."
type: docs
weight: 1500
url: /sv/cpp/system/multicastdelegate_returntype(argumenttypes...)_/operator()/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() method


Invokar alla delegater som för närvarande finns i delegatsamlingen. Delegaterna invokas i samma ordning som de lades till i samlingen. Operatorn blockerar medan delegaterna körs.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | ArgumentTypes... | Argumenten att skicka till delegaterna som ska anropas |

### ReturnValue

Returvärde för den senast anropade delegaten

## Se även

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
