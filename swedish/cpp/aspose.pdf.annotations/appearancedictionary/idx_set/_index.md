---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_set‑metod"
linktitle: "idx_set"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_set‑metod. Representerar ett bekvämt sätt att hämta utseendeströmmar i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.annotations/appearancedictionary/idx_set/
---
## AppearanceDictionary::idx_set method


Representerar ett bekvämt sätt att hämta utseendeströmmar.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::idx_set(const System::String &key, System::SharedPtr<XForm> value) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | const System::String\& | Representerar sökväg till utseendeström. Om appearance dictionary har subdictionaries, måste sökvägen innehålla 2 delar ([Keys](../)), annars har sökvägen bara en del. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
