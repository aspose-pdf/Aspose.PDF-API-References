---
title: Aspose::Pdf::Page::GetPageRect method
linktitle: GetPageRect
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Page::GetPageRect method. Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null) in C++.'
type: docs
weight: 6100
url: /cpp/aspose.pdf/page/getpagerect/
---
## Page::GetPageRect method


Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null).

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Page::GetPageRect(bool considerRotation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation | bool | If true then rotation of the page will be considered in rect calculation. |

### ReturnValue

[Rectangle](../../rectangle/) of the page.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>considerRotation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If true then rotation of the page will be considered in rect calculation.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
