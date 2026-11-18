---
title: System::Text::Json::JsonElement::ArrayEnumerator class
linktitle: ArrayEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonElement::ArrayEnumerator class in C++.'
type: docs
weight: 5400
url: /cpp/system.text.json/jsonelement/arrayenumerator/
---
## ArrayEnumerator class




```cpp
class ArrayEnumerator : public System::Collections::Generic::IEnumerator<JsonElement>,
                        public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [ArrayEnumerator](./arrayenumerator/)() |  |
| [ArrayEnumerator](./arrayenumerator/)(JsonElement, int32_t) |  |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_Current](./get_current/)() const override | Gets current element. |
| [GetEnumerator](./getenumerator/)() |  |
| [MoveNext](./movenext/)() override | Moves enumerator to the next element. If no element was referenced before, sets reference to the first element available. If container end was hit, does nothing. |
| [Reset](./reset/)() override | Resets enumerator to position before first element. |
## See Also

* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [JsonElement](../)
* Namespace [System::Text::Json](../../)
* Library [Aspose.PDF for C++](../../../)
