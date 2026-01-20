---
title: Aspose::Pdf::LoadOptions::MarginsAreaUsageModes enum
linktitle: MarginsAreaUsageModes
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LoadOptions::MarginsAreaUsageModes enum. Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf/loadoptions/marginsareausagemodes/
---
## MarginsAreaUsageModes enum


Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins.

```cpp
enum class MarginsAreaUsageModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | 0 | In this mode converter obeyes format of imported document (f.e. CSS of imported HTML) in usage of margins area.So, if format of imported document requires usage of margins area for rendering , converter will allow that. |
| NeverPutContentOnMarginArea | 1 | This mode strictly forbids usage of margins area, so, converter will never use area of margins for rendering, even if CSS or format of source document allows or requirs that. |

## See Also

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
