---
title: System::IO::WrapSTDIOStream method
linktitle: WrapSTDIOStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::WrapSTDIOStream method. Wrapper function for std::basic_iostream-like streams in C++.'
type: docs
weight: 5400
url: /cpp/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) method


Wrapper function for std::basic_iostream-like streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-like stream |
| mode | STDIOStreamWrappingMode | Wrapping mode |
| pref_pos | STDIOStreamPositionPreference | Position that will prefer as read and write position, if they are different |

### ReturnValue

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Wrapper function for std::basic_istream-like streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-like stream |
| mode | STDIOStreamWrappingMode | Wrapping mode |

### ReturnValue

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Wrapper function for std::basic_ostream-like streams.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-like stream |
| mode | STDIOStreamWrappingMode | Wrapping mode |

### ReturnValue

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
