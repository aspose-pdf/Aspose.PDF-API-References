---
title: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters konstruktor"
linktitle: "ContentsResizeParameters"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters konstruktor. Skapar storleksändringsparametrar där al värden är satta till \"auto\". Senare marginaler och innehållsstorlek kan specificeras om det behövs i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/contentsresizeparameters/
---
## ContentsResizeParameters::ContentsResizeParameters() constructor


Skapar storleksändringsparametrar där alla värden är satta till "auto". Senare kan marginaler och innehållsstorlek specificeras om så krävs.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters()
```

## Se även

* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
## ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) constructor


Skapar storleksändringsparametrar med angivna marginalvärden och innehållsstorlek.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &leftMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsWidth, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &rightMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &topMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsHeight, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Left](../../../../aspose.pdf/left/) marginalvärde. |
| contentsWidth | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Innehållsbredd. |
| rightMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Höger](../../../../aspose.pdf/right/) marginal. |
| topMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Övre marginal. |
| contentsHeight | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Innehållshöjd. |
| bottomMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Nedre marginal. |
## Anmärkningar



Tomma värden betyder att motsvarande värde beräknas automatiskt
## Se även

* Typedef [SharedPtr](../../../../system/sharedptr/)
* Class [ContentsResizeValue](../../contentsresizevalue/)
* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
