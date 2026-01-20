---
title: System::Uri::MakeRelativeUri method
linktitle: MakeRelativeUri
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri::MakeRelativeUri method. Determines the difference between URIs represented by the current and the specified Uri objects in C++.'
type: docs
weight: 3100
url: /cpp/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri method


Determines the difference between URIs represented by the current and the specified [Uri](../) objects.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | The comparand |

### ReturnValue

If the hostname and scheme of the URIs represented by the current object and **toUri** are the same, then this method returns a relative [Uri](../) that, when appended to the current URI instance, yields **toUri**. If the hostname or scheme is different, then this method returns a [Uri](../) object that represents the **uri** parameter.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
