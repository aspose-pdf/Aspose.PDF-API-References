---
title: System::Text::Encodings::Web::JavaScriptEncoder::FindFirstCharacterToEncode method
linktitle: FindFirstCharacterToEncode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encodings::Web::JavaScriptEncoder::FindFirstCharacterToEncode method. Finds the index of the first UTF-16 character that needs to be escaped in C++.'
type: docs
weight: 400
url: /cpp/system.text.encodings.web/javascriptencoder/findfirstcharactertoencode/
---
## JavaScriptEncoder::FindFirstCharacterToEncode method


Finds the index of the first UTF-16 character that needs to be escaped.

```cpp
int32_t System::Text::Encodings::Web::JavaScriptEncoder::FindFirstCharacterToEncode(const char16_t *text, int32_t textLength) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| text | const char16_t * | The UTF-16 text to scan. |
| textLength | int32_t | The number of characters in **text**. |

### ReturnValue

[Index](../../../system/index/) of the first character requiring escaping, or -1 if none.

## See Also

* Class [JavaScriptEncoder](../)
* Namespace [System::Text::Encodings::Web](../../)
* Library [Aspose.PDF for C++](../../../)
