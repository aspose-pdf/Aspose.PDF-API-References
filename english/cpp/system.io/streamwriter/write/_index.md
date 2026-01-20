---
title: System::IO::StreamWriter::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StreamWriter::Write method. Writes the specified character to the stream in C++.'
type: docs
weight: 1000
url: /cpp/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) method


Writes the specified character to the stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The character to write |

## See Also

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&) method


Writes all characetrs from the specified array to the stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | The array containing the characters to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Writes the specified subrange of UTF-16 characters from the specified character array to the stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | The array containing the characters to write |
| index | int32_t | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int32_t | The number of characters in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const char_t *) method


Writes the specified c-string to the stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const char_t * | The c-string to write |

## See Also

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const SharedPtr\<Object\>\&) method


Writes the string representation of the specified object to the stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SharedPtr\<Object\>\& | The object to write |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const String\&) method


Writes the specified string to the stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to write |

## See Also

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const System::SharedPtr\<T\>\&) method


Writes the string representation of the specified object to the stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


| Parameter | Description |
| --- | --- |
| T | The type of the object |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const System::SharedPtr\<T\>\& | The object to write |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
