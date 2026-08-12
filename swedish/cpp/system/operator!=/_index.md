---
title: "System::operator!= metod"
linktitle: "operator!="
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder operator!=-metoden för klassen i C++."
type: docs
weight: 26600
url: /sv/cpp/system/operator!=/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) method




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## Se även

* Class [ArraySegment](../arraysegment/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(Chars\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


| Parameter | Beskrivning |
| --- | --- |
| Chars | [String](../string/) litteraltyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | Chars\& | [String](../string/) litteral att jämföra. |
| right | const String\& | [String](../string/) att jämföra. |

### ReturnValue

false om strängarna matchar, true annars.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SharedPtr\<Object\>\&, const String\&) method


[Object](../object/) and string comparison.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | const SharedPtr\<Object\>\& | [Object](../object/) att konvertera till sträng och jämföra. |
| right | const String\& | [String](../string/) att jämföra. |

### ReturnValue

false om objektets strängrepresentation är lika med strängen, true annars.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) method


Bestämmer om URI:erna som representeras av det aktuella och angivna objektet inte är lika.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | Det första [Uri](../uri/) objektet att jämföra |
| uri2 | const SharedPtr\<Uri\>\& | Det andra [Uri](../uri/) objektet att jämföra |

### ReturnValue

True om URI:erna inte är lika, annars - false

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [Uri](../uri/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) method


Icke-lik jämför två smarta pekare.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


| Parameter | Beskrivning |
| --- | --- |
| X | Pointee-typ för första pekaren. |
| Y | Pointee-typ för andra pekaren. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | Första pekaren att jämföra. |
| y | const SmartPtr\<Y\>\& | Andra pekaren att jämföra. |

### ReturnValue

Falskt om pekarna matchar, sant annars.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const Y *) method


Icke‑likhetsjämförelse av smart pekare mot enkel (C) pekare.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


| Parameter | Beskrivning |
| --- | --- |
| X | typ av smart pekare. |
| Y | typ av enkel pekare. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | smart pekare att jämföra (vänster). |
| y | const Y * | pekare att jämföra (höger). |

### ReturnValue

Falskt om pekarna matchar, sant annars.

## Se även

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const T1\&, const Nullable\<T2\>\&) method


Bestämmer om det angivna värdet inte är lika med värdet som representeras av det angivna [Nullable](../nullable/)-objektet genom att tillämpa [operator!=()](./) på dessa värden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av det första jämförelsevärdet |
| T2 | Den underliggande typen av [Nullable](../nullable/)-objektet som representerar det andra jämförelsevärdet |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| några | const T1\& | En konstant referens till värdet som ska användas som det första jämförelsevärdet |
| other | const Nullable\<T2\>\& | En konstant referens till [Nullable](../nullable/)-objektet vars representerade värde ska användas som det andra jämförelsevärdet |

### ReturnValue

Sant om jämförelsevärdena inte är lika, annars - falskt

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const X *, const SmartPtr\<Y\>\&) method


Likhetsjämförelse av smart pekare mot enkel (C) pekare.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


| Parameter | Beskrivning |
| --- | --- |
| X | typ av enkel pekare. |
| Y | typ av smart pekare. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const X * | pekare att jämföra (höger). |
| y | const SmartPtr\<Y\>\& | smart pekare att jämföra (vänster). |

### ReturnValue

Falskt om pekarna matchar, sant annars.

## Se även

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) method


Kontrollerar om smart pekare inte är null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


| Parameter | Beskrivning |
| --- | --- |
| X | Pekartyp för pekaren. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | SmartPtr\<X\> const\& | Pekare att kontrollera. |

### ReturnValue

Falskt om pekaren är null, sant annars.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## Se även

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) method


Bestämmer om det angivna [Nullable](../nullable/)-objektet representerar ett värde som inte är lika med null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | std::nullptr_t | En konstant referens till ett [Nullable](../nullable/)-objekt att testa |

### ReturnValue

Sant om det angivna objektet representerar ett icke-null-värde, falskt annars

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const String\&) method


Kontrollerar om strängen är null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) för att kontrollera. |

### ReturnValue

falskt om strängen är null, sant annars.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, DateTime) method




```cpp
bool System::operator!=(std::nullptr_t, DateTime)
```

## Se även

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) method


Kontrollerar om smart pekare inte är null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


| Parameter | Beskrivning |
| --- | --- |
| X | Pekartyp för pekaren. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | std::nullptr_t | Pekare att kontrollera. |

### ReturnValue

Falskt om pekaren är null, sant annars.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator!=(std::nullptr_t, TimeSpan)
```

## Se även

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(T\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [String](../string/) pekartyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | T\& | [String](../string/) pekare för jämförelse. |
| right | const String\& | [String](../string/) att jämföra. |

### ReturnValue

false om strängarna matchar, true annars.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
