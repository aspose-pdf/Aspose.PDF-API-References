---
title: "método System::setter_sub_wrap"
linktitle: "setter_sub_wrap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método setter_sub_wrap de la clase en C++."
type: docs
weight: 42600
url: /es/cpp/system/setter_sub_wrap/
---
## System::setter_sub_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_sub_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(const PropT &), PropValT value)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_sub_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(PropT), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_sub_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(PropT), PropValT value)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_sub_wrap(PropT(*)(), void(*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_sub_wrap(PropT(*pGetter)(), void(*pSetter)(const PropT &), PropValT value)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_sub_wrap(PropT(*)(), void(*)(PropT), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_sub_wrap(PropT(*pGetter)(), void(*pSetter)(PropT), PropValT value)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
