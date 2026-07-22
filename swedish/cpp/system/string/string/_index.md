---
title: "System::String::String konstruktor"
linktitle: "String"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::String konstruktor. Standardkonstruktor. Skapar ett strängobjekt som anses vara null i C++."
type: docs
weight: 100
url: /sv/cpp/system/string/string/
---
## String::String() constructor


Standardkonstruktor. Skapar ett strängobjekt som betraktas som null.

```cpp
System::String::String()
```

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(codeporting_icu::UnicodeString\&&) constructor


Flyttkonstruktor.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString att omsluta i [String](../). |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&) constructor


Konverterar hela teckenarrayen till en sträng.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | [Array](../../array/) för att konvertera till sträng. |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor


Konverterar ett delintervall av teckenarrayen till en sträng. Om parametrarna ligger utanför arrayens gränser, skapas en tom sträng.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | Teckenarray. |
| förskjutning | int | Startindex för delarray. |
| len | int | Längd för delarray. |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char *, int) constructor


Konstruerar en sträng från en teckensträngspekare och explicit längd.

```cpp
System::String::String(const char *str, int length)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char * | [String](../) pekare till UTF8-data, kan vara en literal eller en array. |
| längd | int | Explicit stränglängd |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t *, int) constructor


Konstruerar en sträng från en teckensträngspekare och explicit längd.

```cpp
System::String::String(const char16_t *str, int length)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char16_t * | [String](../) pekare, kan vara en literal eller en array. |
| längd | int | Explicit stränglängd |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t *, int, int) constructor


Konstruerar en sträng från en teckensträngspekare från startposition med angiven längd.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char16_t * | [String](../) pekare, kan vara en literal eller en array. |
| start | int | Startposition. |
| length | int | [String](../) längd. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t, int) constructor


Fyllkonstruktor.

```cpp
System::String::String(const char16_t ch, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | const char16_t | Fylltecken. |
| count | int | Mållängd. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const codeporting_icu::UnicodeString\&) constructor


Packar UnicodeString i [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString att omsluta i [String](../). |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ReadOnlySpan\<char16_t\>\&) constructor


Initierar en ny instans av klassen [System.String](../) med de Unicode-tecken som anges i det specificerade skrivskyddade intervallet.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const ReadOnlySpan\<char16_t\>\& | Ett skrivskyddat intervall av Unicode-tecken. |

## Se även

* Class [ReadOnlySpan](../../readonlyspan/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::string\&) constructor


Skapar [String](../) från std::string-sträng presenterad i formatet UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utf8str | const std::string\& | std::string-sträng att konvertera till [String](../). |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::u16string\&) constructor


Skapar [String](../) från utf16-sträng.

```cpp
System::String::String(const std::u16string &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const std::u16string\& | Utf16-sträng att konvertera till [String](../). |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::u32string\&) constructor


Skapar [String](../) från std::u32string-sträng.

```cpp
System::String::String(const std::u32string &u32str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string-sträng att konvertera till [String](../). |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::wstring\&) constructor


Skapar [String](../) från widestring.

```cpp
System::String::String(const std::wstring &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const std::wstring\& | Widestring att konvertera till [String](../). |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const String\&) constructor


Kopieringskonstruktor.

```cpp
System::String::String(const String &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | [String](../) för att kopiera. |

## Se även

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor


Konstruerar en sträng baserat på en teckensträngspekare. Behandlar den pekade strängen som nullterminerad i UTF‑8, beräknar målsträngens längd baserat på nulltecknet.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const T\& | Teckensträngspekare. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor


Konstruerar en sträng baserat på en teckensträngspekare. Behandlar den pekade strängen som nullterminerad, beräknar målsträngens längd baserat på nulltecknet.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const T\& | Teckensträngspekare. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor


Skapar en sträng baserad på pekare till widecharacter-sträng. Behandlar den pekade strängen som nullterminerad, beräknar målsträngens längd baserat på nulltecknet. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const T\& | Teckensträngspekare. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor


Nullptr-konstruktor. Deklarerad som mall för att lösa prioriteringar med andra mallkonstruktorer.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Bör vara nullptr_t |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const T\& | nullptr |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const wchar_t *, int) constructor


Skapar en sträng från pekare till widecharacter-sträng och explicit längd. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
System::String::String(const wchar_t *str, int length)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const wchar_t * | [String](../) pekare, kan vara en literal eller en array. |
| längd | int | Explicit stränglängd |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const wchar_t, int) constructor


Fyllkonstruktor. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | const wchar_t | Fylltecken. |
| count | int | Mållängd. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(String\&&) constructor


Flyttkonstruktor.

```cpp
System::String::String(String &&str) noexcept
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String\&& | [String](../) för att flytta data från. |

## Se även

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor


Konstruerar en sträng baserat på en strängliteral. Betraktar litteralen som en nullterminerad sträng i UTF‑8, beräknar målsträngens längd baserat på litteralens storlek.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | [String](../) literalpekare. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor


Konstruerar en sträng baserat på en strängliteral. Betraktar litteralen som en nullterminerad sträng, beräknar målsträngens längd baserat på litteralens storlek.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | [String](../) literalpekare. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor


Skapar en sträng baserad på widestring-literal. Betraktar litteralen som en nullterminerad sträng, beräknar målsträngens längd baserat på litteralens storlek. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | [String](../) literalpekare. |

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
