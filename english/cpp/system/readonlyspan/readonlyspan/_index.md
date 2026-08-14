---
title: System::ReadOnlySpan::ReadOnlySpan constructor
linktitle: ReadOnlySpan
second_title: Aspose.PDF for C++ API Reference
description: 'System::ReadOnlySpan::ReadOnlySpan constructor. Constructs an empty read-only span in C++.'
type: docs
weight: 100
url: /cpp/system/readonlyspan/readonlyspan/
---
## ReadOnlySpan::ReadOnlySpan() constructor


Constructs an empty read-only span.

```cpp
System::ReadOnlySpan<T>::ReadOnlySpan()
```

## See Also

* Class [ReadOnlySpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySpan::ReadOnlySpan(const Span\<T\>\&) constructor


Constructs a read-only span from a regular span.

```cpp
System::ReadOnlySpan<T>::ReadOnlySpan(const Span<T> &span)
```


| Parameter | Type | Description |
| --- | --- | --- |
| span | const Span\<T\>\& | The span to create a read-only view of. |

## See Also

* Class [Span](../../span/)
* Class [ReadOnlySpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlySpan::ReadOnlySpan(const typename std::enable_if\<std::is_same\<T1, uint8_t\>::value, char\>::type(&)) constructor


Constructs a read-only span from a string literal.

```cpp
template<std::size_t,typename T1> System::ReadOnlySpan<T>::ReadOnlySpan(const typename std::enable_if<std::is_same<T1, uint8_t>::value, char>::type(&array)[N])
```


| Parameter | Description |
| --- | --- |
| N | Literal size. |
| T1 | Serice SFINAE type. |

| Parameter | Type | Description |
| --- | --- | --- |
| array | const typename std::enable_if\<std::is_same\<T1, uint8_t\>::value, char\>::type(&) | The span to create a read-only view of. |

## See Also

* Class [ReadOnlySpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
