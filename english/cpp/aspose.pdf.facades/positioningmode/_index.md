---
title: Aspose::Pdf::Facades::PositioningMode enum
linktitle: PositioningMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PositioningMode enum. Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method) in C++.'
type: docs
weight: 4900
url: /cpp/aspose.pdf.facades/positioningmode/
---
## PositioningMode enum


Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method)

```cpp
enum class PositioningMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Legacy | 0 | Legacy text positioning. |
| ModernLineSpacing | 1 | Updated line spacing, vertical position calculation is done by the old rules (i.e. text is positioned relative to bottom-left corner of the specified rectangle) |
| Current | 2 | Updated line spacing and vertical position calculation is done based on left-top corner rather than left-bottom. |

## See Also

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
