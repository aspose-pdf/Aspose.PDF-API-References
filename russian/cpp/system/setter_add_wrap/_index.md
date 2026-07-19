---
title: "Метод System::setter_add_wrap"
linktitle: "setter_add_wrap"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод setter_add_wrap класса в C++."
type: docs
weight: 37900
url: /ru/cpp/system/setter_add_wrap/
---
## System::setter_add_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_add_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(const PropT &), PropValT value)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_add_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(PropT), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_add_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(PropT), PropValT value)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_add_wrap(PropT(*)(), void(*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_add_wrap(PropT(*pGetter)(), void(*pSetter)(const PropT &), PropValT value)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_add_wrap(PropT(*)(), void(*)(PropT), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_add_wrap(PropT(*pGetter)(), void(*pSetter)(PropT), PropValT value)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
