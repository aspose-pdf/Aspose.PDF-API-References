---
title: "System::operator*-metod"
linktitle: "operator*"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::operator*-metod. Returnerar en ny instans av Decimal-klass som representerar ett värde som är resultatet av multiplikationen av det angivna värdet och värdet som representeras av det angivna Decimal-objektet i C++."
type: docs
weight: 28200
url: /sv/cpp/system/operator_/
---
## System::operator* method


Returnerar en ny instans av [Decimal](../decimal/) klass som representerar ett värde som är resultatet av multiplikationen av det angivna värdet och värdet som representeras av det angivna [Decimal](../decimal/) objektet.

```cpp
template<typename T,typename _> Decimal System::operator*(const T &x, const Decimal &d)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T\& | Den första multiplikatorn |
| d | const Decimal\& | Det [Decimal](../decimal/) objektet som representerar den andra multiplikatorn |

### ReturnValue

En ny instans av [Decimal](../decimal/) klass som representerar ett värde som är resultatet av multiplikationen av **x** och värdet som representeras av **d**.

## Se även

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: System::operator<-metod
linktitle: operator<
second_title: Aspose.PDF för C++ API-referens
description: 'System::operator<-metod. Bestämmer om det angivna värdet är mindre än värdet som representeras av det angivna Nullable-objektet genom att tillämpa operator<() på dessa värden i C++.'
type: dokument
vikt: 29400
url: /cpp/system/operator_/
---
## System::operator<(const T1\&, const Nullable\<T2\>\&) method


Bestämmer om det angivna värdet är mindre än värdet som representeras av det angivna [Nullable](../nullable/) objektet genom att tillämpa [operator<()](./) på dessa värden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
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

Sant om den första jämförelsetermen är mindre än den andra jämförelsetermen, annars - falskt

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## Se även

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, const Nullable\<T\>\&) method


Returnerar alltid falskt.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, DateTime) method




```cpp
bool System::operator<(std::nullptr_t, DateTime)
```

## Se även

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator<(std::nullptr_t, TimeSpan)
```

## Se även

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
titel: System::operator> metod
länktitel: operator>
second_title: Aspose.PDF för C++ API-referens
description: 'System::operator> metod. Bestämmer om det angivna värdet är större än värdet som representeras av det angivna Nullable-objektet genom att tillämpa operator>() på dessa värden i C++.'
type: dokument
vikt: 34900
url: /cpp/system/operator_/
---
## System::operator>(const T1\&, const Nullable\<T2\>\&) method


Bestämmer om det angivna värdet är större än värdet som representeras av det angivna [Nullable](../nullable/) objektet genom att tillämpa [operator>()](./) på dessa värden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
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

Sant om den första jämförelsetermen är större än den andra jämförelsetermen, annars - falskt

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## Se även

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, const Nullable\<T\>\&) method


Returnerar alltid falskt.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, DateTime) method




```cpp
bool System::operator>(std::nullptr_t, DateTime)
```

## Se även

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator>(std::nullptr_t, TimeSpan)
```

## Se även

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
