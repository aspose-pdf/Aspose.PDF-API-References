---
title: Aspose::Pdf::Annotations::AppearanceDictionary::idx_set method
linktitle: idx_set
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AppearanceDictionary::idx_set method. Represents convenient form for getting appearance streams in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.annotations/appearancedictionary/idx_set/
---
## AppearanceDictionary::idx_set method


Represents convenient form for getting appearance streams.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::AppearanceDictionary::idx_set(const System::String &key, System::SharedPtr<XForm> value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Represents path to appearance stream. If appearance dictionary has subdictionaries, then path must contain 2 parts ([Keys](../)), else path has only one part. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Represents path to appearance stream. If appearance dictionary has subdictionaries, then path must contain 2 parts (<ref refid="" kindref="compound">Keys</ref>), else path has only one part. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
