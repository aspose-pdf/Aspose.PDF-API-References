---
title: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters constructor"
linktitle: "ContentsResizeParameters"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters constructor. Crea parámetros de redimensionamiento donde todos los valores se establecen en \"auto\". Más tarde los márgenes y el tamaño del contenido pueden especificarse si es necesario en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/contentsresizeparameters/
---
## ContentsResizeParameters::ContentsResizeParameters() constructor


Crea parámetros de redimensionamiento donde todos los valores se establecen en "auto". Más tarde se pueden especificar los márgenes y el tamaño del contenido si es necesario.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters()
```

## Ver también

* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
## ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) constructor


Crea parámetros de redimensionamiento con los valores de margen especificados y el tamaño del contenido.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &leftMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsWidth, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &rightMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &topMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsHeight, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Left](../../../../aspose.pdf/left/) valor del margen. |
| contentsWidth | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Ancho del contenido. |
| rightMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Right](../../../../aspose.pdf/right/) margen. |
| topMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Margen superior. |
| contentsHeight | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Altura del contenido. |
| bottomMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Margen inferior. |
## Observaciones



Los valores vacíos indican que el valor correspondiente se calcula automáticamente
## Ver también

* Typedef [SharedPtr](../../../../system/sharedptr/)
* Class [ContentsResizeValue](../../contentsresizevalue/)
* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
