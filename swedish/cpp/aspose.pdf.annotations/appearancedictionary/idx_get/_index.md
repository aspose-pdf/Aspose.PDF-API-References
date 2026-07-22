---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_get‑metod"
linktitle: "idx_get"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_get‑metod. Representerar ett bekvämt sätt att hämta utseendeströmmar i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.annotations/appearancedictionary/idx_get/
---
## AppearanceDictionary::idx_get method


Representerar ett bekvämt sätt att hämta utseendeströmmar.

```cpp
System::SharedPtr<XForm> Aspose::Pdf::Annotations::AppearanceDictionary::idx_get(const System::String &key) const override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | const System::String\& | Representerar sökväg till utseendeström. Om appearance dictionary har subdictionaries, måste sökvägen innehålla 2 delar ([Keys](../)), annars har sökvägen bara en del. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [String](../../../system/string/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
