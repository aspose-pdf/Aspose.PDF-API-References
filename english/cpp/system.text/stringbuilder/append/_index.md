---
title: System::Text::StringBuilder::Append method
linktitle: Append
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::StringBuilder::Append method. Adds character to builder in C++.'
type: docs
weight: 300
url: /cpp/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) method


Adds character to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character value. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(char_t, int) method


Adds characters to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character value. |
| count | int | How many times to repeat insertee character. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&) method


Adds characters array to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Characters to add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) method


Adds characters array slice to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


| Parameter | Type | Description |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Characters to add. |
| startIndex | int | Slice beginning index. |
| charCount | int | Slice length. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) method


Adds builder's content to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


| Parameter | Type | Description |
| --- | --- | --- |
| builder | const SharedPtr\<StringBuilder\>\& | Builder to add content from. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<T\>\&) method


Adds object's string representation to builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


| Parameter | Description |
| --- | --- |
| T | [Object](../../../system/object/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SharedPtr\<T\>\& | [Object](../../../system/object/) to serialize and add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&) method


Adds string to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) to add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&, int, int) method


Adds string slice to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) to add. |
| startIndex | int | Slice beginning index. |
| charCount | int | Slice length. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(double) method


Adds floating point value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


| Parameter | Type | Description |
| --- | --- | --- |
| df | double | Value to serialize and add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(E) method


Adds enum value string representation to builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


| Parameter | Description |
| --- | --- |
| E | [Enum](../../../system/enum/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Value to serialize and add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(float) method


Adds floating point value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


| Parameter | Type | Description |
| --- | --- | --- |
| f | float | Value to serialize and add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(int) method


Adds integer value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int | Value to serialize and add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(T) method


Adds arithmetic value to builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


| Parameter | Description |
| --- | --- |
| T | Arithmetic type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | Value to serialize and add. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
