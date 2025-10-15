---
title: System::IterateOver method
linktitle: IterateOver
second_title: Aspose.PDF for C++ API Reference
description: 'System::IterateOver method. This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable this with default target type in C++.'
type: docs
weight: 22100
url: /cpp/system/iterateover/
---
## System::IterateOver(const Enumerable *) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable this with default target type.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parameter | Description |
| --- | --- |
| Enumerable | The type of a wrapped object |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(const Enumerable *) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with target type argument for (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parameter | Description |
| --- | --- |
| T | The target type, it has to be returned from iterator |
| Enumerable | The type of a wrapped object |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with target type argument for (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Description |
| --- | --- |
| T | The target type, it has to be returned from iterator |
| Enumerable | The type of a wrapped object |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with default target type argument for (auto& value : IterateOver(enumerable)) analog to the following C# code foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Description |
| --- | --- |
| Enumerable | The type of a wrapped object |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with default target type argument for (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Description |
| --- | --- |
| Enumerable | The type of a wrapped object |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with target type same as original value_type of iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Description |
| --- | --- |
| Enumerable | The type of a wrapped object |
| T | The target type which has to returned from iterator |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with different target type and original value_type of iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Description |
| --- | --- |
| Enumerable | The type of a wrapped object |
| T | The target type which has to returned from iterator |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
