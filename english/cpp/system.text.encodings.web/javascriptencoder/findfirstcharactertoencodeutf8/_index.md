---
title: System::Text::Encodings::Web::JavaScriptEncoder::FindFirstCharacterToEncodeUtf8 method
linktitle: FindFirstCharacterToEncodeUtf8
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encodings::Web::JavaScriptEncoder::FindFirstCharacterToEncodeUtf8 method. Finds the index of the first UTF-8 byte that needs to be escaped in C++.'
type: docs
weight: 500
url: /cpp/system.text.encodings.web/javascriptencoder/findfirstcharactertoencodeutf8/
---
## JavaScriptEncoder::FindFirstCharacterToEncodeUtf8 method


Finds the index of the first UTF-8 byte that needs to be escaped.

```cpp
int32_t System::Text::Encodings::Web::JavaScriptEncoder::FindFirstCharacterToEncodeUtf8(ReadOnlySpan<uint8_t> utf8Text) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| utf8Text | ReadOnlySpan\<uint8_t\> | The UTF-8 text to scan. |

### ReturnValue

[Index](../../../system/index/) of the first byte requiring escaping, or -1 if none.

## See Also

* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [JavaScriptEncoder](../)
* Namespace [System::Text::Encodings::Web](../../)
* Library [Aspose.PDF for C++](../../../)
