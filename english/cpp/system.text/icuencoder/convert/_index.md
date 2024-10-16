---
title: System::Text::ICUEncoder::Convert method
linktitle: Convert
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ICUEncoder::Convert method. Converts characters to bytes in C++.'
type: docs
weight: 300
url: /cpp/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method


Converts characters to bytes.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters to encode. |
| charIndex | int | Input buffer offset. |
| charCount | int | Input buffer size. |
| bytes | ArrayPtr\<uint8_t\> | Destination byte buffer. |
| byteIndex | int | Destination array offset. |
| byteCount | int | Destination array size. |
| flush | bool | If true, cleans internal encoder state after calculation. |
| charsUsed | int\& | Reference to variable to store count of characters read. |
| bytesUsed | int\& | Reference to variable to store count of bytes written. |
| completed | bool\& | Reference to variable to be set to true if input buffer was exhausted and to false otherwise. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method


Converts characters to bytes.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| charCount | int | Input buffer size. |
| bytes | uint8_t * | Destination byte buffer. |
| byteCount | int | Destination array size. |
| flush | bool | If true, cleans internal encoder state after calculation. |
| charsUsed | int\& | Reference to variable to store count of characters read. |
| bytesUsed | int\& | Reference to variable to store count of bytes written. |
| completed | bool\& | Reference to variable to be set to true if input buffer was exhausted and to false otherwise. |

## See Also

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
