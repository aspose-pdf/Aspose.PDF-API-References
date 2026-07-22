---
title: "System::Collections::Generic::StackPtr klass"
linktitle: "StackPtr"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::StackPtr klass. Stackpekare. Denna typ är en pekare för att hantera andra objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens i C++."
type: docs
weight: 4700
url: /sv/cpp/system.collections.generic/stackptr/
---
## StackPtr class


[Stack](../stack/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<T0>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [StackPtr](./stackptr/)() | Skapar nullpekare. |
| [StackPtr](./stackptr/)(const SharedPtr\<Stack\<T\>\>\&) | Skapar en pekare som refererar till en specifik stack. |

## Se även

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
