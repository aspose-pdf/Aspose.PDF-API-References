---
title: "System::ObjectExt::Equals metod"
linktitle: "Equals"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::Equals metod. Substitution för C# Object.Equals-anrop som fungerar för alla typer i C++. Överlagring för strängliteral med strängjämförelse i C++."
type: docs
weight: 800
url: /sv/cpp/system/objectext/equals/
---
## ObjectExt::Equals(const char_t(&), String) method


Substitution för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för strängliteral med strängjämförelse.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


| Parameter | Beskrivning |
| --- | --- |
| N | [String](../../string/) literalstorlek. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | String | [String](../../string/). |

### ReturnValue

Sant om strängarna matchar, falskt annars.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const double\&, const double\&) method


Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const double\& | LHS flyttalvärde. |
| annan | const double\& | RHS flyttalvärde. |

### ReturnValue

Sant om **obj** och **another** båda är NaN eller lika, annars falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const float\&, const float\&) method


Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const float\& | LHS flyttalvärde. |
| annan | const float\& | RHS flyttalvärde. |

### ReturnValue

Sant om **obj** och **another** båda är NaN eller lika, annars falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för smarta pekartyper.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Första objekttypen. |
| T2 | Andra objekttypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Första objektet. |
| annan | const T2\& | Andra objektet. |

### ReturnValue

Sant om objekt anses vara lika, annars falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för skalära typer.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Första objekttypen. |
| T2 | Andra objekttypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Första objektet. |
| annan | const T2\& | Andra objektet. |

### ReturnValue

Sant om objekt anses vara lika, annars falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(T, const T2\&) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för strukturella typer.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Första objekttypen. |
| T2 | Andra objekttypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | Första objektet. |
| annan | const T2\& | Andra objektet. |

### ReturnValue

Sant om objekt anses vara lika, annars falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
