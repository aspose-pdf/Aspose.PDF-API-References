---
title: Aspose::Pdf::Annotations::AppearanceDictionary::TryGetValue method
linktitle: TryGetValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AppearanceDictionary::TryGetValue method. Tries to find key in the dictionary and retreives value if found in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.annotations/appearancedictionary/trygetvalue/
---
## AppearanceDictionary::TryGetValue method


Tries to find key in the dictionary and retreives value if found.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Annotations::AppearanceDictionary::TryGetValue(const System::String &key, System::SharedPtr<XForm> &value) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key to search in the dictionary. |
| value | System::SharedPtr\<XForm\>\& | Retreived value. |

### ReturnValue

true if key was found.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key to search in the dictionary.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Retreived value.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
