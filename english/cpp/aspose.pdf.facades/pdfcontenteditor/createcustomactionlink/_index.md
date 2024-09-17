---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink method
linktitle: CreateCustomActionLink
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink method. Creates a link to custom actions in PDF document in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor::CreateCustomActionLink method


Creates a link to custom actions in PDF document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink(System::Drawing::Rectangle rect, int32_t originalPage, System::Drawing::Color color, System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> actionName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle for active click. |
| originalPage | int32_t | The number of original page where rectangle bound with link will be created. |
| color | System::Drawing::Color | The colour of rectangle for active click. |
| actionName | System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\> | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The rectangle for active click.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>originalPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of original page where rectangle bound with link will be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>color</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The colour of rectangle for active click.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>actionName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
/// 
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
