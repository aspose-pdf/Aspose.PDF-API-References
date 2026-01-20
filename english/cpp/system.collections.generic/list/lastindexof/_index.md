---
title: System::Collections::Generic::List::LastIndexOf method
linktitle: LastIndexOf
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::List::LastIndexOf method. Searches for the specified object and returns the zero-based index of the last occurrence within the entire list in C++.'
type: docs
weight: 3400
url: /cpp/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const method


Searches for the specified object and returns the zero-based index of the last occurrence within the entire list.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | The object to locate in the list |

### ReturnValue

The zero-based index of the last occurrence of item within the entire the [List](../), if found; otherwise, -1.

## See Also

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::LastIndexOf(const T\&, int32_t) const method


Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the [List](../) that extends from the first element to the specified index.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | The object to locate in the list |
| index | int32_t | The zero-based starting index of the backward search. |

### ReturnValue

The zero-based index of the last occurrence of item within the range of elements in the [List](../) that extends from the first element to index, if found; otherwise, -1.

## See Also

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::LastIndexOf(const T\&, int32_t, int32_t) const method


Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the [List](../) that contains the specified number of elements and ends at the specified index.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | The object to locate in the [List](../) |
| index | int32_t | The zero-based starting index of the backward search. |
| count | int32_t | The number of elements in the section to search. |

### ReturnValue

The zero-based index of the last occurrence of item within the range of elements in the [List](../) that contains count number of elements and ends at index, if found; otherwise, -1.

## See Also

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
