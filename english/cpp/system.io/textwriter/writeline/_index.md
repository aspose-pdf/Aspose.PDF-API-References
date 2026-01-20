---
title: System::IO::TextWriter::WriteLine method
linktitle: WriteLine
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextWriter::WriteLine method. Writes line terminator characters to the stream in C++.'
type: docs
weight: 1000
url: /cpp/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() method


Writes line terminator characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(bool) method


Writes the string representation of the specified boolean value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | bool | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(char_t) method


Writes the specified character followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) method


Writes all characetrs from the specified array followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | The array containing the characters to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Writes the specified subrange of UTF-16 characters from the specified character array followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
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
## TextWriter::WriteLine(const char_t *) method


Writes the specified c-string followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const SharedPtr\<Object\>\&) method


Writes the string representation of the specified object followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
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
## TextWriter::WriteLine(const String\&, const TArgs\&...) method


Writes the specified values formatted according to the specified format followed by the line-terminating characetrs to the stream.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
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
## TextWriter::WriteLine(const String\&) method


Writes the specified string followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to write |

## See Also

* Class [String](../../../system/string/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const TypeInfo\&) method


Writes the string representation of the specified [TypeInfo](../../../system/typeinfo/) object followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const TypeInfo\& | The object to write |

## See Also

* Class [TypeInfo](../../../system/typeinfo/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(Decimal) method


Writes the string representation of the specified [Decimal](../../../system/decimal/) object followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | Decimal | The object to write |

## See Also

* Class [Decimal](../../../system/decimal/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(double) method


Writes the string representation of the specified double-precision floating point value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(float) method


Writes the string representation of the specified single-precision floating point value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(int) method


Writes the string representation of the specified 32-bit integer value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(int64_t) method


Writes the string representation of the specified 64-bit integer value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | int64_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(uint32_t) method


Writes the string representation of the specified unsigned 32-bit integer value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | uint32_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(uint64_t) method


Writes the string representation of the specified unsigned 64-bit integer value followed by the line-terminating characters to the stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | uint64_t | The value to write |

## See Also

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
