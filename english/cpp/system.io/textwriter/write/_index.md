---
title: System::IO::TextWriter::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextWriter::Write method. Writes the string representation of the specified boolean value to the stream in C++.'
type: docs
weight: 900
url: /cpp/system.io/textwriter/write/
---
## TextWriter::Write(bool) method


Writes the string representation of the specified boolean value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | bool | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(char_t) method


Writes the specified character to the stream.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const ArrayPtr\<char_t\>\&) method


Writes all characetrs from the specified array to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | The array containing the characters to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Writes the specified subrange of UTF-16 characters from the specified character array to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | The array containing the characters to write |
| index | int32_t | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of characters in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const char_t *) method


Writes the specified c-string to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const SharedPtr\<Object\>\&) method


Writes the string representation of the specified object to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const SharedPtr\<Object\>\& | The object to write |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const String\&, const TArgs\&...) method


Writes the specified values formatted according to the specified format to the stream.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


| Parameter | Description |
| --- | --- |
| TArgs | The list of types of values to write |

| Parameter | Type | Description |
| --- | --- | --- |
| format | const String\& | The string format |
| args | const TArgs\&... | The values to write |

## See Also

* Class [String](../../../system/string/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const String\&) method


Writes the specified string to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to write |

## See Also

* Class [String](../../../system/string/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(const TypeInfo\&) method


Writes the string representation of the specified [TypeInfo](../../../system/typeinfo/) object to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const TypeInfo\& | The object to write |

## See Also

* Class [TypeInfo](../../../system/typeinfo/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(Decimal) method


Writes the string representation of the specified [Decimal](../../../system/decimal/) object to the stream.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | Decimal | The object to write |

## See Also

* Class [Decimal](../../../system/decimal/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(double) method


Writes the string representation of the specified double-precision floating point value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(float) method


Writes the string representation of the specified single-precision floating point value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(int) method


Writes the string representation of the specified 32-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(int64_t) method


Writes the string representation of the specified 64-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | int64_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(uint32_t) method


Writes the string representation of the specified unsigned 32-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | uint32_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::Write(uint64_t) method


Writes the string representation of the specified unsigned 64-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | uint64_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
