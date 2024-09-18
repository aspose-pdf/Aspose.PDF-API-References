---
title: Aspose::Pdf::Facades::PdfXmpMetadata::TryGetValue method
linktitle: TryGetValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfXmpMetadata::TryGetValue method. Tries to find key in the dictionary and retreives value if found in C++.'
type: docs
weight: 2000
url: /cpp/aspose.pdf.facades/pdfxmpmetadata/trygetvalue/
---
## PdfXmpMetadata::TryGetValue method


Tries to find key in the dictionary and retreives value if found.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfXmpMetadata::TryGetValue(const System::String &key, System::SharedPtr<XmpValue> &value) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key to search in the dictionary. |
| value | System::SharedPtr\<XmpValue\>\& | Retreived value. |

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

* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
