---
title: System::Text::Json::JsonMemoryMarshal::Cast method
linktitle: Cast
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::JsonMemoryMarshal::Cast method. Casts a read-only span of one primitive type TFrom to another primitive type TTo in C++.'
type: docs
weight: 100
url: /cpp/system.text.json/jsonmemorymarshal/cast/
---
## JsonMemoryMarshal::Cast method


Casts a read-only span of one primitive type TFrom to another primitive type TTo.

```cpp
template<typename TFrom,typename TTo> static ReadOnlySpan<TTo> System::Text::Json::JsonMemoryMarshal::Cast(const ReadOnlySpan<TFrom> &span)
```


| Parameter | Description |
| --- | --- |
| TFrom | The source type of the span. |
| TTo | The target type of the span. |

| Parameter | Type | Description |
| --- | --- | --- |
| span | const ReadOnlySpan\<TFrom\>\& | The span to cast. |

### ReturnValue

A read-only span of the target type.

## See Also

* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [JsonMemoryMarshal](../)
* Namespace [System::Text::Json](../../)
* Library [Aspose.PDF for C++](../../../)
