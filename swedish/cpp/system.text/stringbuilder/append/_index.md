---
title: "System::Text::StringBuilder::Append metod"
linktitle: "Append"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::StringBuilder::Append metod. Lägger till tecken till byggaren i C++."
type: docs
weight: 300
url: /sv/cpp/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) method


Lägger till tecken i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Teckenvärde. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(char_t, int) method


Lägger till tecken i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Teckenvärde. |
| count | int | Hur många gånger insatta tecken ska upprepas. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&) method


Lägger till teckenarray i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Tecken att lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) method


Lägger till del av teckenarray i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Tecken att lägga till. |
| startIndex | int | Skivans startindex. |
| charCount | int | Skivlängd. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) method


Lägger till byggarens innehåll i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byggare | const SharedPtr\<StringBuilder\>\& | Byggare att lägga till innehåll från. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<T\>\&) method


Lägger till objektets strängrepresentation i byggaren.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../../system/object/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SharedPtr\<T\>\& | [Object](../../../system/object/) att serialisera och lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&) method


Lägger till sträng i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) att lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&, int, int) method


Lägger till del av sträng i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) att lägga till. |
| startIndex | int | Skivans startindex. |
| charCount | int | Skivlängd. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(double) method


Lägger till flyttal i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| df | double | Värde att serialisera och lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(E) method


Lägger till enumvärdets strängrepresentation i byggaren.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


| Parameter | Beskrivning |
| --- | --- |
| E | [Enum](../../../system/enum/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | E | Värde att serialisera och lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(float) method


Lägger till flyttal i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | float | Värde att serialisera och lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(int) method


Lägger till heltal i byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int | Värde att serialisera och lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(T) method


Lägger till aritmetiskt värde i byggaren.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Aritmetisk typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | T | Värde att serialisera och lägga till. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
