---
title: "System::Collections::IList-klass"
linktitle: "IList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::IList-klass. IList representerar en icke-generisk samling av objekt som kan nås individuellt via index i C++."
type: docs
weight: 1000
url: /sv/cpp/system.collections/ilist/
---
## IList class


[IList](./) Represents a non-generic collection of objects that can be individually accessed by index.

```cpp
class IList : public virtual System::Collections::ICollection
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Add](./add/)(SharedPtr\<System::Object\>) | Lägger till ett objekt i slutet av listan. |
| virtual [Clear](./clear/)() | Tar bort alla objekt från listan. |
| virtual [Contains](./contains/)(SharedPtr\<System::Object\>) const | Kontrollerar om objektet finns i listan. |
| virtual [get_IsFixedSize](./get_isfixedsize/)() const | Hämtar ett värde som indikerar om listan har en fast storlek. |
| virtual [idx_get](./idx_get/)(int, int) const | RTTI-information. |
| virtual [IndexOf](./indexof/)(SharedPtr\<System::Object\>) const | Hämtar det första indexet för det angivna objektet. |
| virtual [Insert](./insert/)(int, SharedPtr\<System::Object\>) | Infogar objektet i listan på det angivna indexet. |
| virtual [Remove](./remove/)(SharedPtr\<System::Object\>) | Tar bort den första förekomsten av det angivna objektet från listan. |
| virtual [RemoveAt](./removeat/)(int) | Tar bort objektet från listan på det angivna indexet. |
## Se även

* Class [ICollection](../icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
