---
title: Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters constructor
linktitle: ContentsResizeParameters
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters constructor. Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/contentsresizeparameters/
---
## ContentsResizeParameters::ContentsResizeParameters() constructor


Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters()
```

## See Also

* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
## ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) constructor


Creates resize parameters with specified margin values and contents size.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &leftMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsWidth, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &rightMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &topMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsHeight, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &bottomMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| leftMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Left](../../../../aspose.pdf/left/) margin value. |
| contentsWidth | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Contents width. |
| rightMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Right](../../../../aspose.pdf/right/) margin. |
| topMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Top margin. |
| contentsHeight | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Contents height. |
| bottomMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Bottom margin. |
## Remarks



Empty values means that corresponding value calculated automatically 
## See Also

* Typedef [SharedPtr](../../../../system/sharedptr/)
* Class [ContentsResizeValue](../../contentsresizevalue/)
* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
