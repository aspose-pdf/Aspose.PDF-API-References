---
title: Aspose::Pdf::DocumentExtensions::SplitSharedImages method
linktitle: SplitSharedImages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocumentExtensions::SplitSharedImages method. For Images in Resources if two pages checks for common XImages and for similar cases splits them, by creating duplicate XImages in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/documentextensions/splitsharedimages/
---
## DocumentExtensions::SplitSharedImages method


For Images in [Resources](../../resources/) if two pages checks for common XImages and for similar cases splits them, by creating duplicate XImages.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::DocumentExtensions::SplitSharedImages(System::SharedPtr<Document> doc, System::SharedPtr<Page> page_1, System::SharedPtr<Page> page_2)
```


| Parameter | Type | Description |
| --- | --- | --- |
| doc | System::SharedPtr\<Document\> | The document containing both collections. |
| page_1 | System::SharedPtr\<Page\> | First page for compare. |
| page_2 | System::SharedPtr\<Page\> | Second page for compare/ |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>doc</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document containing both collections.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page_1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>First page for compare.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page_2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Second page for compare/</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [Page](../../page/)
* Class [DocumentExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
