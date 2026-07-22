---
title: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters klass"
linktitle: "ContentsResizeParameters"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters klass. Klass för att specificera sidans storleksändringsparametrar. Tillåter att ange följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vänster, topp, botten och höger marginaler i standardenhetsmått eller i procent av den ursprungliga sidstorleken; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter att explicit angivna värden beräknats. Till exempel: om sidbredd = 100 och ny sidbredd anges till 60 enheter så beräknas vänster- och högermarginalerna automatiskt: (100 - 60) / 2 = 15. Denna klass används i ResizeContents metod i C++."
type: docs
weight: 7300
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/
---
## ContentsResizeParameters class


Klassen för att specificera sidans storleksändringsparametrar. Tillåter att ange följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; [Left](../../../aspose.pdf/left/), Top, Bottom och [Right](../../../aspose.pdf/right/) marginaler i standardenhetsmått eller i procent av den ursprungliga sidstorleken; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter att explicit angivna värden beräknats. Till exempel: om sidbredd = 100 och ny sidbredd anges till 60 enheter så beräknas vänster- och högermarginalerna automatiskt: (100 - 60) / 2 = 15. Denna klass används i ResizeContents metod.

```cpp
class ContentsResizeParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ContentSize](./contentsize/)(double, double) | Skapar storleksändringsparametrar med angiven innehållsstorlek. |
| static [ContentSizePercent](./contentsizepercent/)(double, double) | Skapar storleksändringsparametrar med angiven innehållsstorlek i procent av den ursprungliga sidstorleken. Marginaler beräknas automatiskt. |
| [ContentsResizeParameters](./contentsresizeparameters/)() | Skapar storleksändringsparametrar där alla värden är satta till "auto". Senare kan marginaler och innehållsstorlek specificeras om så krävs. |
| [ContentsResizeParameters](./contentsresizeparameters/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Skapar storleksändringsparametrar med angivna marginalvärden och innehållsstorlek. |
| [get_BottomMargin](./get_bottommargin/)() const | Hämtar bottenmarginal på den resulterande sidan. |
| [get_ChangeMediaBox](./get_changemediabox/)() const | Hämtar och anger om MediaBox för en PDF-sida ska justeras under storleksändringsoperationen. Standardvärdet är **false** |
| [get_ContentsHeight](./get_contentsheight/)() const | Hämtar höjden på innehållet från källsidan på den resulterande sidan. |
| [get_ContentsWidth](./get_contentswidth/)() const | Hämtar bredden på innehållet från källsidan på den resulterande sidan. |
| [get_LeftMargin](./get_leftmargin/)() const | Hämtar vänstermarginal på den resulterande sidan. |
| [get_RightMargin](./get_rightmargin/)() const | Hämtar högermarginal på den resulterande sidan. |
| [get_TopMargin](./get_topmargin/)() const | Hämtar toppmarginal på den resulterande sidan. |
| static [Margins](./margins/)(double, double, double, double) | Skapar storleksändringsparametrar med specificerade marginalvärden. Innehållsstorlek beräknas automatiskt. |
| static [MarginsPercent](./marginspercent/)(double, double, double, double) | Skapar storleksändringsparametrar. Marginaler specificeras i procent av den ursprungliga sidstorleken. |
| static [PageResize](./pageresize/)(double, double) | Skapar storleksändringsparametrar för sidändring. |
| static [PageResizePct](./pageresizepct/)(double, double) | Skapar storleksändringsparametrar för sidändring. Nya storlekar specificeras i procent. |
| [set_BottomMargin](./set_bottommargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Ställer in bottenmarginal på den resulterande sidan. |
| [set_ChangeMediaBox](./set_changemediabox/)(bool) | Hämtar och anger om MediaBox för en PDF-sida ska justeras under storleksändringsoperationen. Standardvärdet är **false** |
| [set_ContentsHeight](./set_contentsheight/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Ställer in höjden på innehållet från källsidan på den resulterande sidan. |
| [set_ContentsWidth](./set_contentswidth/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Ställer in bredden på innehållet på källsidan på den resulterande sidan. |
| [set_LeftMargin](./set_leftmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Ställer in vänstermarginalen på den resulterande sidan. |
| [set_RightMargin](./set_rightmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Ställer in högermarginalen på den resulterande sidan. |
| [set_TopMargin](./set_topmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Ställer in övre marginalen på den resulterande sidan. |
## Se även

* Class [Object](../../../system/object/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
