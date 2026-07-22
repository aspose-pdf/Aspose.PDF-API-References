---
title: "System::Uri::Compare metod"
linktitle: "Compare"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Uri::Compare metod. Jämför de angivna Uri‑objekten med de angivna jämförelsereglerna i C++."
type: docs
weight: 3500
url: /sv/cpp/system/uri/compare/
---
## Uri::Compare method


Jämför de angivna [Uri](../)‑objekten med de angivna jämförelsereglerna.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | Den första jämförelsetermen |
| uri2 | const SharedPtr\<Uri\>\& | Den andra jämförelsetermen |
| partsToCompare | UriComponents | Anger delarna av **uri1** och **uri2** som ska jämföras |
| compareFormat | UriFormat | Anger teckenescape som används när komponenter av URI:er jämförs |
| comparisonType | StringComparison | Ett av värdena i [StringComparison](../../stringcomparison/) |

### ReturnValue

Ett negativt värde om **uri1** är mindre än **uri2**; 0 om uri1 och uri2 är lika; ett positivt värde om **uri1** är större än **uri2**

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
