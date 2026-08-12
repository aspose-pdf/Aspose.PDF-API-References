---
title: "Método System::IO::WrapSTDIOStream"
linktitle: "WrapSTDIOStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::WrapSTDIOStream. Función contenedora para flujos tipo std::basic_iostream en C++."
type: docs
weight: 5400
url: /es/cpp/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) method


Función contenedora para flujos tipo std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | std::basic_iostream\<char_type, traits_type\>\& | flujo tipo std::basic_iostream |
| modo | STDIOStreamWrappingMode | Modo de envoltura |
| pref_pos | STDIOStreamPositionPreference | Posición que se preferirá como posición de lectura y escritura, si son diferentes. |

### ReturnValue

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Función contenedora para flujos tipo std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | std::basic_istream\<char_type, traits_type\>\& | flujo tipo std::basic_istream |
| modo | STDIOStreamWrappingMode | Modo de envoltura |

### ReturnValue

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) method


Función contenedora para flujos tipo std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | std::basic_ostream\<char_type, traits_type\>\& | flujo similar a std::basic_ostream |
| modo | STDIOStreamWrappingMode | Modo de envoltura |

### ReturnValue

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
