---
title: System::Text::Json::JsonMemoryMarshal::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::JsonMemoryMarshal::Write method. Writes a value of type T to the beginning of the specified byte span in C++.'
type: docs
weight: 300
url: /cpp/system.text.json/jsonmemorymarshal/write/
---
## JsonMemoryMarshal::Write method


Writes a value of type T to the beginning of the specified byte span.

```cpp
template<typename T> static void System::Text::Json::JsonMemoryMarshal::Write(const Span<uint8_t> &destination, T &value)
```


| Parameter | Description |
| --- | --- |
| T | The type of the value to write. |

| Parameter | Type | Description |
| --- | --- | --- |
| destination | const Span\<uint8_t\>\& | The byte span to write to. |
| value | T\& | The value to write. |

## See Also

* Class [Span](../../../system/span/)
* Class [JsonMemoryMarshal](../)
* Namespace [System::Text::Json](../../)
* Library [Aspose.PDF for C++](../../../)
