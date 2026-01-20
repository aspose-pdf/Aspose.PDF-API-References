---
title: System::Resources::ResourceManager::GetObject__ method
linktitle: GetObject__
second_title: Aspose.PDF for C++ API Reference
description: 'System::Resources::ResourceManager::GetObject__ method. Gets object from resource. Name is not GetObject() to deal with GetObjectA define issue in C++.'
type: docs
weight: 200
url: /cpp/system.resources/resourcemanager/getobject__/
---
## ResourceManager::GetObject__(String) method


Gets object from resource. Name is not GetObject() to deal with GetObjectA define issue.

```cpp
virtual SharedPtr<Object> System::Resources::ResourceManager::GetObject__(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Resource name. |

### ReturnValue

Requested resource.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [ResourceManager](../)
* Namespace [System::Resources](../../)
* Library [Aspose.PDF for C++](../../../)
## ResourceManager::GetObject__(String, SharedPtr\<System::Globalization::CultureInfo\>) method


Gets object from resource. Name is not GetObject() to deal with GetObjectA define issue.

```cpp
virtual SharedPtr<Object> System::Resources::ResourceManager::GetObject__(String name, SharedPtr<System::Globalization::CultureInfo> culture)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Resource name. |
| culture | SharedPtr\<System::Globalization::CultureInfo\> | Culture to use when decoding names. |

### ReturnValue

Requested resource.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [ResourceManager](../)
* Namespace [System::Resources](../../)
* Library [Aspose.PDF for C++](../../../)
