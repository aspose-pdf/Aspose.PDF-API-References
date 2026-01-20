---
title: System::Uri::Compare method
linktitle: Compare
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri::Compare method. Compares the specified Uri objects using the specified comparison rules in C++.'
type: docs
weight: 3500
url: /cpp/system/uri/compare/
---
## Uri::Compare method


Compares the specified [Uri](../) objects using the specified comparison rules.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | The first comparand |
| uri2 | const SharedPtr\<Uri\>\& | The second comparand |
| partsToCompare | UriComponents | Specifies the parts of **uri1** and **uri2** to compare |
| compareFormat | UriFormat | Specifies the character escaping used when components of URIs are compared |
| comparisonType | StringComparison | One of the [StringComparison](../../stringcomparison/) values |

### ReturnValue

A negative value if **uri1** is less than **uri2**; 0 if uri1 and uri2 are equal; a positive value if **uri1** is greater than **uri2**

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
