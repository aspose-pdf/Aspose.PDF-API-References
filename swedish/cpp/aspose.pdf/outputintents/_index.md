---
title: "Aspose::Pdf::OutputIntents class"
linktitle: "OutputIntents"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OutputIntents class. Representerar samlingen av OutputIntent i C++."
type: docs
weight: 12900
url: /sv/cpp/aspose.pdf/outputintents/
---
## OutputIntents class


Representerar samlingen av [OutputIntent](../outputintent/).

```cpp
class OutputIntents : public System::Collections::Generic::ICollection<System::SharedPtr<OutputIntent>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutputIntent\>\&) override | Lägger till ett output‑intent i samlingen. |
| [Clear](./clear/)() override | Tar bort alla output‑intents från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<OutputIntent\>\&) const override | Avgör om samlingen innehåller ett specifikt output‑intent. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutputIntent\>\>, int32_t) override | Kopierar elementen i samlingen till *array*, med start vid det specifika *arrayIndex* i arrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet utdataintentioner som finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar utdataintentionen vid det angivna *index*. |
| [Remove](./remove/)(const System::SharedPtr\<OutputIntent\>\&) override | Tar bort den första förekomsten av en specifik utdataintention från samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
