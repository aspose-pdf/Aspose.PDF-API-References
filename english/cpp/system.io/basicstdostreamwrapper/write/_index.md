---
title: System::IO::BasicSTDOStreamWrapper::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BasicSTDOStreamWrapper::Write method. If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream in C++.'
type: docs
weight: 700
url: /cpp/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to [char_type](../char_type/) type ant then writes result to the stream.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The array containing the bytes to write |
| offset | int32_t | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | The array view containing the bytes to write |
| offset | int32_t | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
