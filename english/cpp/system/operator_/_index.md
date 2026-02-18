---
title: System::operator* method
linktitle: operator*
second_title: Aspose.PDF for C++ API Reference
description: 'System::operator* method. Returns a new instance of Decimal class that represents a value that is a result of multiplication of the specified value and the value represented by the specified Decimal object in C++.'
type: docs
weight: 27500
url: /cpp/system/operator_/
---
## System::operator* method


Returns a new instance of [Decimal](../decimal/) class that represents a value that is a result of multiplication of the specified value and the value represented by the specified [Decimal](../decimal/) object.

```cpp
template<typename T,typename _> Decimal System::operator*(const T &x, const Decimal &d)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | The first multiplier |
| d | const Decimal\& | The [Decimal](../decimal/) object representing the second multiplier |

### ReturnValue

A new instance of [Decimal](../decimal/) class that represents a value that is a result of multiplication of **x** and the value represented by **d**.

## See Also

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: System::operator< method
linktitle: operator<
second_title: Aspose.PDF for C++ API Reference
description: 'System::operator< method. Determines if the specified value is less than the value represented by the specified Nullable object by applying operator<() to these values in C++.'
type: docs
weight: 28700
url: /cpp/system/operator_/
---
## System::operator<(const T1\&, const Nullable\<T2\>\&) method


Determines if the specified value is less than the value represented by the specified [Nullable](../nullable/) object by applying [operator<()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const Nullable\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### ReturnValue

True if the first comparand is less than the second comparand, otherwise - false

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, const Nullable\<T\>\&) method


Always returns false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, DateTime) method




```cpp
bool System::operator<(std::nullptr_t, DateTime)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator<(std::nullptr_t, TimeSpan)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: System::operator> method
linktitle: operator>
second_title: Aspose.PDF for C++ API Reference
description: 'System::operator> method. Determines if the specified value is greater than the value represented by the specified Nullable object by applying operator>() to these values in C++.'
type: docs
weight: 34200
url: /cpp/system/operator_/
---
## System::operator>(const T1\&, const Nullable\<T2\>\&) method


Determines if the specified value is greater than the value represented by the specified [Nullable](../nullable/) object by applying [operator>()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const Nullable\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### ReturnValue

True if the first comparand is greater than the second comparand, otherwise - false

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, const Nullable\<T\>\&) method


Always returns false.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, DateTime) method




```cpp
bool System::operator>(std::nullptr_t, DateTime)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator>(std::nullptr_t, TimeSpan)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
