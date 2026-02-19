---
title: System::MakeObject method
linktitle: MakeObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeObject method. Creates object on heap and returns shared pointer to it in C++.'
type: docs
weight: 24600
url: /cpp/system/makeobject/
---
## System::MakeObject(Args\&&...) method


Creates object on heap and returns shared pointer to it.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


| Parameter | Description |
| --- | --- |
| T | Class to instantiate. |
| Args | Constructor arguments' types. |

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Constructor arguments. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeObject(Args\&&...) method


Creates object on heap and returns shared pointer to it.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


| Parameter | Description |
| --- | --- |
| T | [SmartPtr](../smartptr/) to class to instantiate. |
| Args | Constructor arguments' types. |

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Constructor arguments. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
