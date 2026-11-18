---
title: System::Text::Json::Serialization::Metadata::UnboxRef method
linktitle: UnboxRef
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::Serialization::Metadata::UnboxRef method. Unboxes a boxed value type to a mutable reference allowing in-place modification of the boxed value. Supports BoxedValue<T> wrappers only, for value types not derived from Object in C++.'
type: docs
weight: 2400
url: /cpp/system.text.json.serialization.metadata/unboxref/
---
## System::Text::Json::Serialization::Metadata::UnboxRef(const SmartPtr\<Object\>\&) method


Unboxes a boxed value type to a mutable reference allowing in-place modification of the boxed value. Supports [BoxedValue<T>](../../system/boxedvalue/) wrappers only, for value types not derived from [Object](../../system/object/).

```cpp
template<class T> std::enable_if<!std::is_enum<T>::value &&IsBoxable<T>::value &&!std::is_base_of<Object, T>::value, T &>::type System::Text::Json::Serialization::Metadata::UnboxRef(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Value type not derived from [Object](../../system/object/). |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../system/object/) to unbox. |

### ReturnValue

Mutable reference to the stored value.

## See Also

* Class [Object](../../system/object/)
* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
## System::Text::Json::Serialization::Metadata::UnboxRef(const SmartPtr\<Object\>\&) method


Unboxes a boxed value type to a mutable reference allowing in-place modification of the boxed value. Supports both [BoxedValue<T>](../../system/boxedvalue/) wrappers and raw T instances.

```cpp
template<class T> std::enable_if<!std::is_enum<T>::value &&IsBoxable<T>::value &&std::is_base_of<Object, T>::value, T &>::type System::Text::Json::Serialization::Metadata::UnboxRef(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Value type derived from [Object](../../system/object/). |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../system/object/) to unbox. |

### ReturnValue

Mutable reference to the stored value.

## See Also

* Class [Object](../../system/object/)
* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
