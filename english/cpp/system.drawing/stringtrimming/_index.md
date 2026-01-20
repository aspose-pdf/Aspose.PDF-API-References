---
title: System::Drawing::StringTrimming enum
linktitle: StringTrimming
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::StringTrimming enum. Specifies how characters should be trimmed from a string that does not fit the layout shape in C++.'
type: docs
weight: 3800
url: /cpp/system.drawing/stringtrimming/
---
## StringTrimming enum


Specifies how characters should be trimmed from a string that does not fit the layout shape.

```cpp
enum class StringTrimming
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No trimming. |
| Character | 1 | Trim to the nearest character. |
| Word | 2 | Trim to the nearest word. |
| EllipsisCharacter | 3 | Trim to the nearest character and insert ellipsis at the end of the string. |
| EllipsisWord | 4 | Trim to the nearest word and insert ellipsis at the end of the string. |
| EllipsisPath | 5 | The center is removed from trimmed lines and replaced by an ellipsis. Keep as much of the last slash-delimited segment of the line as possible. |

## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
