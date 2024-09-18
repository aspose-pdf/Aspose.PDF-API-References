---
title: Aspose::Pdf::Engine::CommonData::Text::CMaps::ICMapCodeSpaceRange class
linktitle: ICMapCodeSpaceRange
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Engine::CommonData::Text::CMaps::ICMapCodeSpaceRange class. Declares a functionality for codespace ranges used by all CMaps in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.engine.commondata.text.cmaps/icmapcodespacerange/
---
## ICMapCodeSpaceRange class


Declares a functionality for codespace ranges used by all [CMaps](../).

```cpp
class ICMapCodeSpaceRange : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetAllBytes](./getallbytes/)(System::Details::ArrayView\<uint8_t\>, System::Details::ArrayView\<uint8_t\>) | Gets codespace range data - all start and end bytes. |
| virtual [GetSize](./getsize/)() | Returns size for codespace range. |
| virtual [HasPartialMatch](./haspartialmatch/)(System::ArrayPtr\<uint8_t\>, int32_t) | Detects is the passed raw code represented in byte array form has a partial match with CMap's codespace ranges - partial match means that first element(s) in array is in range(s) but all the raw code bytes are not fully in any range. |
| virtual [IsInRange](./isinrange/)(uint8_t) | Detects is passed code belongs to codespace range. |
| virtual [IsInRange](./isinrange/)(System::ArrayPtr\<uint8_t\>, int32_t) | Detects is passed code, represented as array of bytes belongs to codespace range. |
| virtual [IsInRange](./isinrange/)(char16_t) | Detects is passed code belongs to codespace range. |
| virtual [IsInRange](./isinrange/)(System::ArrayPtr\<char16_t\>, int32_t) | Detects is passed code, represented as array of chars belongs to codespace range. |
## See Also

* Namespace [Aspose::Pdf::Engine::CommonData::Text::CMaps](../)
* Library [Aspose.PDF for C++](../../)
