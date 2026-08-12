---
title: "Метод System::IO::WrapSTDIOStream"
linktitle: "WrapSTDIOStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::WrapSTDIOStream. Функция‑обёртка для потоков, похожих на std::basic_iostream, в C++."
type: docs
weight: 5400
url: /ru/cpp/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) method


Функция‑обёртка для потоков, похожих на std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | std::basic_iostream\<char_type, traits_type\>\& | Поток, похожий на std::basic_iostream |
| режим | STDIOStreamWrappingMode | Режим обёртывания |
| pref_pos | STDIOStreamPositionPreference | Позиция, которая будет предпочтительной для чтения и записи, если они различаются |

### ReturnValue

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Функция‑обёртка для потоков, похожих на std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | std::basic_istream\<char_type, traits_type\>\& | Поток, похожий на std::basic_istream |
| режим | STDIOStreamWrappingMode | Режим обёртывания |

### ReturnValue

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Функция‑обёртка для потоков, похожих на std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | std::basic_ostream\<char_type, traits_type\>\& | Поток, похожий на std::basic_ostream |
| режим | STDIOStreamWrappingMode | Режим обёртывания |

### ReturnValue

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
