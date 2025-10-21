---
title: System::String::Format method
linktitle: Format
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::Format method. Formats string in C# style in C++.'
type: docs
weight: 6500
url: /cpp/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method


Formats string in C# style.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```


| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

| Parameter | Type | Description |
| --- | --- | --- |
| fp | const SharedPtr\<IFormatProvider\>\& | Format provider to use to convert arguments to strings. |
| format | const String\& | Format string. |
| args | const Args\&... | Arguments to format string. |

## See Also

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Format(const String\&, const Args\&...) method


Formats string in C# style.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```


| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

| Parameter | Type | Description |
| --- | --- | --- |
| format | const String\& | Format string. |
| args | const Args\&... | Arguments to format string. |

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method


Formats string in C# style.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```


| Parameter | Description |
| --- | --- |
| T | Arguments to format string. |

| Parameter | Type | Description |
| --- | --- | --- |
| format | const String\& | Format string. |
| args | const System::ArrayPtr\<T\>\& | Arguments to format string. |

## See Also

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method


Formats string in C# style.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```


| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

| Parameter | Type | Description |
| --- | --- | --- |
| format | std::nullptr_t | Format string. |
| args | const char16_t(&) | Arguments to format string. |

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Format(std::nullptr_t, const String\&, const Args\&...) method


Formats string in C# style.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```


| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

| Parameter | Type | Description |
| --- | --- | --- |
| format | std::nullptr_t | Format string. |
| args | const String\& | Arguments to format string. |

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
