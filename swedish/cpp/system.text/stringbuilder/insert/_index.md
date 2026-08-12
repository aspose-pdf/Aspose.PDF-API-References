---
title: "System::Text::StringBuilder::Insert metod"
linktitle: "Infoga"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::StringBuilder::Insert metod. Infogar tecken i builderns fasta position i C++."
type: docs
weight: 1300
url: /sv/cpp/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) method


Infogar tecken i builderns fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga tecken i. |
| chars | const System::ArrayPtr\<char_t\>\& | [Array](../../../system/array/) att infoga del från. |
| startIndex | int | [Array](../../../system/array/) delens startindex. |
| charCount | int | [Array](../../../system/array/) delens längd. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, char_t) method


Infogar tecken i builderns fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Position att infoga tecken i. |
| ch | char_t | Tecken att infoga. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, const String\&) method


Infogar sträng i builderns fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Position att infoga tecken i. |
| str | const String\& | [String](../../../system/string/) att infoga. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, T) method


Infogar värde i builderns fasta position.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


| Parameter | Beskrivning |
| --- | --- |
| Parameter | typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Position att infoga tecken i. |
| värde | T | Värde att formatera och infoga. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int32_t, const String\&, int32_t) method


Infogar upprepad sträng i builderns fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Position att infoga tecken i. |
| value | const String\& | [String](../../../system/string/) att infoga. |
| count | int32_t | Hur många gånger **value**-strängen ska upprepas. |

### ReturnValue

Denna pekare.

## Se även

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
