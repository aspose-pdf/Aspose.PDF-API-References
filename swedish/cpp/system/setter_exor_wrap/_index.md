---
title: "System::setter_exor_wrap method"
linktitle: "setter_exor_wrap"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder setter_exor_wrap‑metoden för en klass i C++."
type: docs
weight: 39400
url: /sv/cpp/system/setter_exor_wrap/
---
## System::setter_exor_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_exor_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(const PropT &), PropValT value)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_exor_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(PropT), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_exor_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(PropT), PropValT value)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_exor_wrap(PropT(*)(), void(*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_exor_wrap(PropT(*pGetter)(), void(*pSetter)(const PropT &), PropValT value)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_exor_wrap(PropT(*)(), void(*)(PropT), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_exor_wrap(PropT(*pGetter)(), void(*pSetter)(PropT), PropValT value)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
