---
title: Aspose::Pdf::Annotations::AppearanceDictionary::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AppearanceDictionary::idx_get method. Represents convenient form for getting appearance streams in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.annotations/appearancedictionary/idx_get/
---
## AppearanceDictionary::idx_get method


Represents convenient form for getting appearance streams.

```cpp
System::SharedPtr<XForm> Aspose::Pdf::Annotations::AppearanceDictionary::idx_get(const System::String &key) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Represents path to appearance stream. If appearance dictionary has subdictionaries, then path must contain 2 parts ([Keys](../)), else path has only one part. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [String](../../../system/string/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
