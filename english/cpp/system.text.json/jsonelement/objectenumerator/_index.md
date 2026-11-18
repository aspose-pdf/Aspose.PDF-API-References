---
title: System::Text::Json::JsonElement::ObjectEnumerator class
linktitle: ObjectEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonElement::ObjectEnumerator class in C++.'
type: docs
weight: 5500
url: /cpp/system.text.json/jsonelement/objectenumerator/
---
## ObjectEnumerator class




```cpp
class ObjectEnumerator : public System::Collections::Generic::IEnumerator<JsonProperty>,
                         public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_Current](./get_current/)() const override | Gets current element. |
| [GetEnumerator](./getenumerator/)() |  |
| [MoveNext](./movenext/)() override | Moves enumerator to the next element. If no element was referenced before, sets reference to the first element available. If container end was hit, does nothing. |
| [ObjectEnumerator](./objectenumerator/)() |  |
| [ObjectEnumerator](./objectenumerator/)(JsonElement, int32_t) |  |
| [Reset](./reset/)() override | Resets enumerator to position before first element. |
## See Also

* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [JsonElement](../)
* Namespace [System::Text::Json](../../)
* Library [Aspose.PDF for C++](../../../)
