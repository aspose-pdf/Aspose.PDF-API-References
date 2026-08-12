---
title: "System::Collections::Generic::ListExt::CreateIListWrapperImpl method"
linktitle: "CreateIListWrapperImpl"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::ListExt::CreateIListWrapperImpl‑metod. IListWrapper‑implementeringshjälp för referenstyper i C++."
type: docs
weight: 200
url: /sv/cpp/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for reference types.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for value types.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for other types.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
