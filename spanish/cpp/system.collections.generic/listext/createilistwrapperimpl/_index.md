---
title: "System::Collections::Generic::ListExt::CreateIListWrapperImpl método"
linktitle: "CreateIListWrapperImpl"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::ListExt::CreateIListWrapperImpl método. Asistente de implementación de IListWrapper para tipos de referencia en C++."
type: docs
weight: 200
url: /es/cpp/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for reference types.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Ver también

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

## Ver también

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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
