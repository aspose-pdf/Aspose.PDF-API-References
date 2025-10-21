---
title: System::setter_div_wrap method
linktitle: setter_div_wrap
second_title: Aspose.PDF for C++ API Reference
description: 'How to use setter_div_wrap method of  class in C++.'
type: docs
weight: 36900
url: /cpp/system/setter_div_wrap/
---
## System::setter_div_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_div_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(const PropT &), PropValT value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_div_wrap(HostT *const, PropT(HostGetT::*)(), void(HostSetT::*)(PropT), PropValT) method




```cpp
template<typename PropT,typename HostT,typename HostGetT,typename HostSetT,typename PropValT> std::enable_if<std::is_base_of<HostGetT, HostT>::value &&std::is_base_of<HostSetT, HostT>::value, PropT>::type System::setter_div_wrap(HostT *const host, PropT(HostGetT::*pGetter)(), void(HostSetT::*pSetter)(PropT), PropValT value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_div_wrap(PropT(*)(), void(*)(const PropT\&), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_div_wrap(PropT(*pGetter)(), void(*pSetter)(const PropT &), PropValT value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_div_wrap(PropT(*)(), void(*)(PropT), PropValT) method




```cpp
template<typename PropT,typename PropValT> PropT System::setter_div_wrap(PropT(*pGetter)(), void(*pSetter)(PropT), PropValT value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
