---
title: "System::Text::DecoderFallbackBuffer::Fallback метод"
linktitle: "Fallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::DecoderFallbackBuffer::Fallback метод. Реализует фактическую процедуру отката в C++."
type: docs
weight: 100
url: /ru/cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback method


Реализует фактическую процедуру отката.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) байтов, включая тот, который декодер не может декодировать. |
| index | int | [Index](../../../system/index/) байта, вызвавшего ошибку. |

### ReturnValue

True, если буфер обрабатывает неизвестные байты, false, если игнорирует их.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
