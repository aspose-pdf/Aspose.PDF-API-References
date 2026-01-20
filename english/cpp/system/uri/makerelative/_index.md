---
title: System::Uri::MakeRelative method
linktitle: MakeRelative
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri::MakeRelative method. Determines the difference between two Uri instances in C++.'
type: docs
weight: 3000
url: /cpp/system/uri/makerelative/
---
## Uri::MakeRelative method


Determines the difference between two [Uri](../) instances.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| toUri | const SharedPtr\<Uri\>\& | The URI to compare to the current URI |

### ReturnValue

If the hostname and scheme of the URIs represented by the current object and **toUri** are the same, then this method returns a [String](../../string/) that represents a relative [Uri](../), when appended to the current URI instance, yields **toUri**. If the hostname or scheme is different, then this method returns a [String](../../string/) that represents the **uri** parameter.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
