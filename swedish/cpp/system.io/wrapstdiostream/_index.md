---
title: "System::IO::WrapSTDIOStream‑metod"
linktitle: "WrapSTDIOStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::WrapSTDIOStream‑metod. Omslutningsfunktion för std::basic_iostream‑liknande strömmar i C++."
type: docs
weight: 5400
url: /sv/cpp/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) method


Omslutningsfunktion för std::basic_iostream‑liknande strömmar.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream‑liknande ström |
| läge | STDIOStreamWrappingMode | Omslutningsläge |
| pref_pos | STDIOStreamPositionPreference | Position som föredras som läs‑ och skrivposition om de är olika |

### ReturnValue

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Omslutningsfunktion för std::basic_istream‑liknande strömmar.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream‑liknande ström |
| läge | STDIOStreamWrappingMode | Omslutningsläge |

### ReturnValue

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Omslutningsfunktion för std::basic_ostream‑liknande strömmar.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream‑liknande ström |
| läge | STDIOStreamWrappingMode | Omslutningsläge |

### ReturnValue

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
